# libscoreboard
libscoreboard
# documents
## 1. General
```php
use galaxygames\scoreboard\Scoreboard;
...
class EgPlugin extends PluginBase{
  protected Scoreboard $scoreboard;

  public function onEnable() : void{
    $this->scoreboard = Scoreboard::getInstance();
  }
}
```

### 1.1 Create scoreboard
```php
/**
 * @var Player $player
 * @var string $objectiveName
 * @var string $displayName
 */
$this->scoreboard->create($player, $objectiveName, $displayName)
```
### 1.2 Remove scoreboard
```php
$this->scoreboard->remove($player)
```
### 1.3 Change display name
```php
/** @var string $newDisplayName */
$this->scoreboard->setDisplayName($player, $newDisplayName);
```
## 2. Lines
> **Important**
These following instructions won't immediately show the changed line to player, they are required to send this code after the changes in requirement to get it shown to player!<br>
```php
$this->scoreboard->update($player)
```
### Set scoreboard line
```php
/** @var int $line Line number, range from 0 to 15*/
/** @var string $context Context of the line*/
$this->scoreboard->setLine($player, $line, $context);
```
Example:
```php
$this->scoreboard->setLine($player, 0, "line 1");
$this->scoreboard->setLine($player, 4, "line 4");
```
but the scoreboard won't have lines between 0 and 4... that is why floodLine existed!
```php
/** @var int $start The start line which it will flood, default: 0*/
/** @var int $end The end line where the flood end, default: 15*/
/** @var string $flood The line in the range will be flooded by this value, default: ""*/
$this->scoreboard->floodLine($player, $start, $end, $flood);
```
Example:
```php
$this->scoreboard->floodLine($player, 0, 3, "hello"); // Flood from line 0 to line 3 with "hello"
$this->scoreboard->floodLine($player, 4, 14); // Flood from line 4 to line 14 with empty line
```
### Remove a line
```php
/** @var bool $brutal The removal will remove the line without putting an empty line if
this is true, default: fault */
$this->scoreboard->removeLine($player, $line, $brutal);
```
Example:
```php
$this->scoreboard->removeLine($player, 1); //Remove line 1 and leave behind an empty line
$this->scoreboard->removeLine($player, 0); //Remove line 0 without leave behind an empty line
```

You can also be able to do something like this:
```php
$this->scoreboard->create($player, "board", "My board")
    ->setLine($player, 0, "line 0")
    ->floodLine($player, 1, 12)
    ->setLine($player, 13, "line 13")
    ->removeLine($player, 9)
    ->update($player);
```
### Other functions

```php
Scoreboard::getObjectiveName(Player $player); // Return the current scoreboard's name of a player
Scoreboard::clearPlayerCache(Player $player); // This should be called when player left the server
Scoreboard::clearCache(); // Clear all data
```

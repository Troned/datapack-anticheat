# Datapack Anticheat

## Install
After downloading the version that you want, simply move it into the datapacks folder located in
```
%appdata%\.minecraft\saves\{YOUR WORLD}\datapacks
```
Depending on your operating system this may differ.

## Setup
On the world that you installed the datapack onto, type
```
/reload
```
This will then load the datapack into the world.

To set up the anticheat in versions 0.3 and later, you must first type
```
/function ac:autochecks
```

## Features
* Jesus detection
* Flight detection
* Speed detection
* Xray detection
* Kilaura detection
* Nofall detection

* Enabling and disabling checks

## Changelog
### 0.8
* Killaura detection now disabled by default as it was very buggy on servers with a lot of command blocks
* Levitation will no longer false detect

### 0.7
* Wurst fightbot now will detect
* Slow falling wont activate nofall checks

### 0.6
* Fixed nofall false activating occasionally if the server lagged

### 0.5
* Fixed issue where disabling the speed check would break other checks
* Fixed issues with nofall

### 0.4
* Fixed major issue where players could be teleported across the map
* Fixed minor issues such as players getting detected for nofall after landing on a slime block

### 0.3
* Added a feature to lag back players
* Added a feature to toggle checks

### 0.2
* Fixed issues with speed and killaura

## Notes
Feel free to branch this project, just make sure to credit me.

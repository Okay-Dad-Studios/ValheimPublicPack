# Explore Together
A collection of map tweaks aimed to improve cooperative play.

Client side only, no server install required.

* = Other players need the mod for this feature to work

##Pings
- Create a ping where you are looking when you press a configurable key (T by default)
- Adds the coordinates of a ping to the message shown in chat in the form (x, y)

##Minimap
- Other players will reveal areas on the map near their position
- Display your players current coordinates in the small minimap
- Display the coordinates of your cursor in the large map
- Type /sharemap to share your map exploration progress *

##Pins
- Type /sharepins to send your pins to other players *
- Share individual pins by middle clicking and holding a configurablle key *
- Pins created by other players will be added to your map *
- Share your death marker with other players *
- Tag your death marker with your name and time of death
- Track boats and carts on the map

#ChangeLog
### 1.3.0 - (18/03/2021)
- [Contributed by Barril] Share individual pins by pressing middle mouse while hovering over them (and optionally holding an additional key)

### 1.2.2 - (11/03/2021)
- Fixed log spamming "0 0" etc. when cart pins were enabled
- Ships and carts way below sea level will not be shown as pins

### 1.2.1 - (10/03/2021)
- Improved performance of boat and cart detection - boats and carts may take a moment before appearing on the map

### 1.2.0 - (09/03/2021)
- Added a config option to adjust the exclusion range for received pins. This should help if you end up with lots of overlapping pins.
- Added pins for boats and carts to minimap

### 1.1.2 - (01/03/2021)
- Fixed player pins not appearing for all connected players

### 1.1.1 - (26/02/2021)
- Fixed hotkey config for sharing map

### 1.1.0 - (26/02/2021)
- Fixed infinite death pin spam (Very sorry for this!)
- Fix to repair maps affected by infinite death pin spam
- Added hotkey options for sharing map (F10) and sharing pins (F9), change bindings in the config file
- Tweaked log messages to be more descriptive

Source: https://github.com/rolopogo/ValheimMods

Install with BepInEx

Copy ExploreTogether.dll into Valheim/BepInEx/plugins
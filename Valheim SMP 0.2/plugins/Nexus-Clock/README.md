This mod adds a simple but highly configurable time display to the game.


Config

You can set:
the clock's position on the screen either in pixels or percent (it defaults to top-middle).
the font name to use (see below)
the font size of the clock text
the color and transparency of the clock text
a hotkey to toggle the clock display and an optional modifier key (e.g. "left shift")
the time format (either something like HH:mm:ss or set to fuzzy to use specified time strings)
the actual displayed string to surround the the time with (including simple html tags)

You can also customize the fuzzy strings, which are used to divide the day up into custom intervals.

Clock format follows this syntax:

https://docs.microsoft.com/en-us/dotnet/standard/base-types/custom-date-and-time-format-strings


To change the mod's settings, edit the file BepInEx/config/aedenthorn.Clock.cfg (created after running the game once with this mod) using a text editor.

To reload the config from the config file while in the game, open the console (F5) and type clockmod reset then hit Enter.

Fonts

By default, the mod now uses the game's UI font, AveriaSerifLibre-Bold. If you want to use a different font, here's a list of fonts currently available in the game:

Arial

AveriaSerifLibre-Light
AveriaSerifLibre-Regular
AveriaSerifLibre-Bold
AveriaSerifLibre-Italic
AveriaSerifLibre-BoldItalic

AveriaSansLibre-Light
AveriaSansLibre-Regular
AveriaSansLibre-Bold
AveriaSansLibre-Italic
AveriaSansLibre-LightItalic
AveriaSansLibre-BoldItalic

OpenSans-Light
OpenSans-Regular
OpenSans-LightItalic
OpenSans-Italic
OpenSans-BoldItalic
OpenSans-SemiBold
OpenSans-Bold
OpenSans-ExtraBold
OpenSans-SemiBoldItalic
OpenSans-ExtraBoldItalic

Norse
Norsebold

prstart
prstartk
rune

Just change ClockFontName to one of these.

If you want to use a font installed on your OS (this is untested), set ClockUseOSFont to true and provide the name of your font file, e.g. Arial.ttf. Let me know if it doesn't work.


To install this mod, the easiest way is to just use Vortex, the Nexus Mods mod manager. It should take care of all dependencies.

To install manually, place the dll file in the BepInEx/plugins folder. You will need BepInEx.

Code is at https://github.com/aedenthorn/ValheimMods.

﻿﻿If you want to complain or ask for help or help me test my mods, you can visit my Discord server﻿.

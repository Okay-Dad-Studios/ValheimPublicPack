# Stats Logger
Ever wanted to know how many Boars you killed? Or how many times you've Jumped? (And died to gravity)

Look no further, this and many more things can be achieved with the Valheim Stats Logger Mod.

View your current Characters Stats In-Game and watch them increase to questionable amounts.

![Console Example](https://images.givenameplz.de/valheim/gnp_StatsLogger/display.png)

## Features
* Character based Stats logging
* Display Stats In-Game (Inventory Menu->Compendium (Raven Symbol)->Character Stats)
* View Retail Stats already logged by Valheim in the background (Kills, Deaths, Builds, Crafts)
 * Info: The Kills stat is not used by the game yet, but the Mod will start increasing it. (Opt-Out)
* Local Milestone Announcements (Configurable)

## Future Development
* Website for displaying stats online (Opt-In)
* Improved local saving / General file format
* Display more Stats (There is more logged in the Background already than being shown)
* Add more Stats (Whenever something seems reasonable)
* Possible sharing feature to annoy other people on the same server. (Chat Announcements)
* Improve the Display Names of the Stats

## Installation (Manual)
1. Install the [BepInEx](https://valheim.thunderstore.io/package/denikson/BepInExPack_Valheim/) Mod.
2. Copy the `gnp_StatsLogger` folder into `<GameRoot>\BepInEx\plugins`.
3. Start the Game and press `F5` to type `/statslogger` in the console for usage and setup!

## Uninstall
This mod is save to uninstall, it will not corrupt your savegame.

## Settings / Configuration
In-Game with handy Console commands:

![Console Example](https://images.givenameplz.de/valheim/gnp_StatsLogger/console.png)
```
/help - Default command has been handily expanded to also include this mod.
/statslogger chat true/false - Turn on/off Stat-Milestones in the local Chatbox.
/statslogger console true/false - Turn on/off Stat-Milestones in the In-Game Console. (F5)
/statslogger effect true/false - Turn on/off Stat-Milestones "LevelUp" effect and GUI-Message.
/statslogger cooldown <number> - Set the Stat-Milestone announcement cooldown (0 to display everything, not recommended)
/statslogger inckills true/false - Enable/Disable the mod from increasing the Retail Kill value of Valheim. (Valheim has not yet used it)
/statslogger retail - View the Valheim Retail Stats.
/statslogger reset - Resets the stats of the current Character.
```

## Contact / Feedback
If you feel like dropping a message about something feel free to head to the [Website](https://givenameplz.de) to find contact information, or even better on [Discord](https://discord.com/invite/W8j6gvR).

## Changelog
### 1.1.0
* Added a custom window which replaces the view in the Compendium to fix having too many stats breaking the display (might see some more work down the road)
* Added categories to the custom window which includes all the "handcrafted" stat selections
* Added a "Weapons" category to the categories in the custom window
* Added a search function to the custom window
* Added a "raw" view to the custom window which will show you every stat currently logged
* Removed the entries in the Compendium but one, which now acts as button to open the StatsLogger window
* Added logging for LastDeath (time)
* Added logging for LastDamageTaken (time)
* Changed display for "time" based values to a 00:00:00 format
* Added the mod icon as sprite for the stat announce effect, it's not an empty white square anymore now

### 1.0.1
* Fixed some Stats not correctly logging in Multiplayer. *(Special thanks to [Drebonda](https://www.twitch.tv/drebonda) & [Daniel](https://www.twitch.tv/dannyboy1060) for acting as test subjects.)*
* Hiding unnecessary debug outputs.
* Changed BepInEx dependency from 5.4.602 to 5.4.800.

### 1.0.0
* Initial release
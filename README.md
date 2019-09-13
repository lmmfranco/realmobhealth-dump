# Real Mob Health addon complete database
Mob health data extracted from Lights Hope (Elysium) database, as requested by /u/Lucrise on /r/wowaddons 

This dump follows the same logic as [elysium-mobhealth3-extract](https://github.com/Jakobud/lights-hope-mobhealth3-extract), which consists in using the mean between min and max health in case it is not the same value.

## Usage

For this to work you must have [Real Mob Health addon](https://www.curseforge.com/wow/addons/real-mob-health) installed.

If you don't care about the current data on your RMH database just copy `RealMobHealth.lua` over to the folder `World of Warcraft/WTF/Account/<ACCOUNT NAME>/SavedVariables/`

If you want to merge it manually open `CreatureHealthCache.lua` and merge it with your local `RealMobHealth.lua` file.
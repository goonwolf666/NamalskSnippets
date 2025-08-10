# AI Missions config for Namalsk
## For servers using xplosiff/Merkzone's ["Dynamic AI Missions for DayZ Expansion AI"](https://steamcommunity.com/sharedfiles/filedetails/?id=3277130230) mod.


Notes:
* There are two options to used in your 'MainConfig.json' file: one with vanilla loot and vehicles as reward, and one with expansion vehicles and weapons.
* To install, download the relevant json file to your *profile\AIMissions* folder, and rename it to 'MainConfig.json'. As always, it's recommended to rename existing files to retain them as a backup.
* The AI Missions are mostly located south of the Namalsk map, generally near military, remote or lore areas.
* These missions are designed to replace the wider vehicle spawns - so players dont get to drive or fly without cleaning up a mission first. You might want to adjust your existing events.xml to wind back the 'natural' vehicle spawns.
* I use [CJ187's Loot Chest](https://steamcommunity.com/workshop/filedetails/?id=2345073965) mod, so the 'win' loot includes certain keys in the special loot - you will want to remove or customise these.
* There is only a single type of 'win' heli - you might want to add more here.
* The vehicles spawn in at mission start, but you won't get all the required gear to start them until you clear the AI.
* I have set the timing for mission start/cleanup processes to be slightly eccentric, as I found spawning more than one mission at time made them start in close "waves".
* This has been tested on a live server and works fine (although we don't use map markers, so not sure if that works as intended).
* If you change any values, remember to use a [JSON validator to check your syntax](https://jsonlint.com/) afterward =)

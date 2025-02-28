#Namalsk Locker Shipping Containers
##These code snippets add the locked shipping containers from DayZ 1.27 to servers running the Namalsk mod.

* Containers spawn on the iceflows and islands around the map, mostly within the view of the shore.
* There are 37 possible spawn locations, including a few distant spawns (Bering, the Sub and Oilrig).
* The 'StaticContainerLocked' event is configured to spawn at least one container of each colored lock. 
* Container keys are configured to spawn in military tool loot positions, inside tier 4, 5 & 6 zones.
* Container keys will be between 55% and 85% damaged, to give each key a limited number of uses.
* Containers themselves are configured to spawn military loot, with tags to include rifles and Namalsk lore.
		
The combined XML file here has small snippets you need to install in five different server files:
* db\types.xml    (this manages how keys and containers behave in the central loot economy)
* db\events.xml   (this manages how many and which specific containers spawn in the events)
* cfgspawnabletypes.xml    (this manages the damage that the keys spawns in with)
* cfgeventspawns.xml    (this manages all possible locations that container events can spawn at)
* mapgroupproto.xml    (this manages where and what kind of loot appears in the containers)

Note that each server XML file has its own start and end tags. It is recommended to paste these snippets near the bottom of each file but before the final closing tag, or at the very top right after the opening tag =)

Namalsk has some unique settings for it's central economy, and these changes have been tested successfully.

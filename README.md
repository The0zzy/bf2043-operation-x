# Operation-X

![Operation-X](/docs/images/OPERATION_X_-_WORK_IN_PROGRESS.png "Operation-X")

This is a Battlefield 2042 Portal game mode built in cooperation of the BF2043 and Portal Community Discord Servers.

## How the game mode works

- It is like rush - there is one attacking team and the other is defending
- There are 2 sectors per map and 2 M-COMs per sector.
- The map is loaded with the first sector, and after both M-COMs have been successfully armed and destroyed, the players are moved to the second sector.
- The attacking team has a limited amount of tickets represented as score of the team
- Whenever an M-COM gets armed, the fusetime is ticking down - if it gets defused and then armed again, it will continue on the left fusetime instead of starting over at the initial fusetime

### Specialties

- A teleporter that catapults the player 100-200m into the sky.
  - Depending on the map and its sector, it should favor defenders more.
  - It is always available, but it takes 5-10 seconds to eject the player when standing on/interacting with the icon.
  - The insertion icon is positioned behind cover and the ejection icon is positioned in the sky - to eject the player.
- Weapon battle pickup
  - activates every 2 minutes and lasts for the given amount of time once picked up
  - Spawns randomly at one of multiple pickup locations
  - Contains following items:
    - Sniper - BF3 M98B with script damage, 1-shots, lasts 20 seconds.
    - Tanker - BC2 M249 SAW along with an invincibility buff that lasts for 10 seconds.
    - Rocketer - 1942 Bazooka that uses infinite ammo and fires very fast, but lasts only 5 seconds.
- Gadget battle pickup
  - Activates every 1 minute and lasts for the given amount of time once picked up
  - Spawns randomly at one of multiple pickup locations
  - Contains following items:
    - Smoker - BF3 M18 Smoke Grenade has infinite ammo, lasts 40 seconds.
    - Gunship - BC2 Mortar Strike no cooldown after three seconds of targeting, lasts 30 seconds.
    - Demolisher - 1942 ExpPack has infinite ammo, lasts 20 seconds.

## Base Settings

- Based on custom Team Deathmatch
- sliding disabled
- minimap enabled
- compass enabled
- 2042 specialists and their traits, but weapon and gadget loadout (BF2042 era + vault weapons) is randomized upon each deployment
- 40 players / 20v20 with PVP AI
- maximum round time 20 minutes
- Infantry only
- 10 maps supported
- AI spawns as random specialist

## Balance

- Random shuffle of teams at the start of each new map
- Random loadouts to avoid meta-weapons only
- 5 second spawn protection


## MAPS & SECTORS:

- Breakaway
  - Road Checkpoint
  - Outlook Station
- Orbital
  - Beach
  - Radar Station
- Exposure
  - Tactical Outpost
  - Road Landslide
- Flashpoint
  - Container Checkpoint
  - Army Base
- Caspian Border
  - Runway Outpost
  - Hangers
- Arica Harbor
  - First Stage
  - Border Control
- Manifest
  - Jungle Checkpoint
  - Beach
- Kaleidoscope
  - Skatepark
  - Towers
- Discarded
  - Road Entrance
  - Dismantling Side
- Battle of the Bulge
  - Wooden Workshop
  - Armored Column

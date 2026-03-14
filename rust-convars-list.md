**⚙️ COMMON RUST SERVER CONVARS (CONSOLE VARIABLES) ⚙️**

Here is a list of the most common console variables (convars) that server owners like to customize. If you want any of these changed from their default values, just let us know in your ticket and we will add them to your server's startup configuration!

**🏚️ DECAY & UPKEEP**
* `decay.scale` (Default: 1) - Multiplier for base decay damage. Set to `0` to completely disable decay. Set to `0.5` for half decay.
* `decay.upkeep` (Default: true) - Set to `false` to completely disable the Tool Cupboard upkeep system.
* `decay.upkeep_period_minutes` (Default: 1440) - How many minutes of upkeep a full TC provides (1440 = 24 hours). Increase this to make upkeep last longer.

**🚁 VEHICLE POPULATIONS**
*(Note: 0 disables them from spawning naturally in the wild)*
* `minicopter.population` (Default: 0) - Set higher (e.g., 1 or 2) to allow minicopters to spawn on roads again.
* `scraptransporthelicopter.population` (Default: 0) - Set higher to allow scrap helis to spawn naturally.
* `motorrowboat.population` (Default: 2) - Number of rowboats spawning along the coast.
* `rhib.population` (Default: 1) - Number of RHIBs spawning along the coast.
* `hotairballoon.population` (Default: 1) - Number of hot air balloons spawning.
* `horse.population` (Default: 2) - Number of horses spawning in the wild.

**🐻 ANIMAL POPULATIONS**
*(Increase to add more animals, decrease or set to 0 for fewer/none)*
* `bear.population` (Default: 2)
* `boar.population` (Default: 5)
* `wolf.population` (Default: 2)
* `stag.population` (Default: 3)
* `chicken.population` (Default: 3)

**🌞 DAY & NIGHT CYCLE**
* `env.daylength` (Default: 45) - How long daytime lasts, in minutes.
* `env.nightlength` (Default: 15) - How long nighttime lasts, in minutes.
* `env.time` - Can be used to lock the server to a specific time of day (though usually better managed via plugins if you want permanent day).

**🌍 GENERAL SERVER SETTINGS**
* `server.pve` (Default: false) - Set to `true` to enable native PvE mode (players cannot damage each other or each other's bases).
* `server.radiation` (Default: true) - Set to `false` to completely disable radiation at all monuments.
* `server.globalchat` (Default: true) - Set to `false` to disable global text chat (players can only hear voice chat or local text).
* `server.saveinterval` (Default: 600) - How often the server saves the map, in seconds (600 = 10 minutes).
* `server.censorplayerlist` (Default: false) - Set to `true` to hide the player list from being queried by server trackers (adds privacy).
* `server.maxplayers` - The maximum number of players allowed on the server.

*Don't see what you're looking for? Just ask! There are hundreds of convars, but these are the ones most frequently requested.*
**⚙️ COMPLETE RUST SERVER CONVARS (CONSOLE VARIABLES) ⚙️**

*Note to clients: This is a comprehensive list of server-side console variables. If you see something you want changed from the default, let us know!*

**🌍 SERVER SETTINGS**
* `server.hostname` - The name of the server.
* `server.description` - The description shown in the server browser.
* `server.url` - The website link for the server.
* `server.headerimage` - The banner image URL (512x256).
* `server.logoimage` - The circular logo image URL (256x256).
* `server.maxplayers` - Maximum number of players allowed.
* `server.worldsize` - Size of the map (default 4500).
* `server.seed` - The map generation seed.
* `server.saveinterval` - Seconds between map saves (default 600).
* `server.pve` - Enable PvE mode (default false).
* `server.radiation` - Enable/disable radiation globally (default true).
* `server.globalchat` - Enable/disable global text chat (default true).
* `server.censorplayerlist` - Hide player list from server queries (default false).
* `server.idlekick` - Minutes before an AFK player is kicked (default 30).
* `server.idlekickmode` - 0 = no kick, 1 = kick if server full, 2 = always kick.
* `server.idlekickadmins` - Whether admins get idle kicked (default false).
* `server.itemdespawn` - Seconds before dropped items despawn (default 300).
* `server.corpsedespawn` - Seconds before player corpses despawn (default 300).
* `server.debrisdespawn` - Seconds before destroyed building debris despawns (default 30).
* `server.woundingenabled` - Enable/disable the wounded state (default true).
* `server.crawlingenabled` - Enable/disable crawling when wounded (default true).
* `server.fallfalldamage` - Enable/disable fall damage (default true).
* `server.meleedamage` - Multiplier for melee damage (default 1).
* `server.arrowdamage` - Multiplier for arrow damage (default 1).
* `server.bulletdamage` - Multiplier for bullet damage (default 1).
* `server.bleedingdamage` - Multiplier for bleeding damage (default 1).
* `server.tickrate` - Server tick rate (default 30).

**🏚️ DECAY & UPKEEP**
* `decay.scale` - Global multiplier for decay damage (default 1). Set to 0 to disable.
* `decay.upkeep` - Enable/disable Tool Cupboard upkeep (default true).
* `decay.upkeep_period_minutes` - Minutes of upkeep a full TC provides (default 1440).
* `decay.upkeep_inside_decay_scale` - Decay scale for items inside (default 0.1).
* `decay.delay_twig` - Hours before twig starts decaying (default 0).
* `decay.delay_wood` - Hours before wood starts decaying (default 0).
* `decay.delay_stone` - Hours before stone starts decaying (default 0).
* `decay.delay_metal` - Hours before metal starts decaying (default 0).
* `decay.delay_toptier` - Hours before armored starts decaying (default 0).
* `decay.duration_twig` - Hours it takes for twig to fully decay (default 1).
* `decay.duration_wood` - Hours it takes for wood to fully decay (default 3).
* `decay.duration_stone` - Hours it takes for stone to fully decay (default 5).
* `decay.duration_metal` - Hours it takes for metal to fully decay (default 8).
* `decay.duration_toptier` - Hours it takes for armored to fully decay (default 12).

**👥 TEAM & CLAN**
* `relationshipmanager.maxteamsize` - Maximum number of players in a UI team (default 8).
* `clan.enabled` - Enable native clan system (default false).
* `clan.maxMemberCount` - Maximum clan members (default 100).

**🌞 ENVIRONMENT & WEATHER**
* `env.time` - Set the current time of day (0-24).
* `env.daylength` - Length of daytime in minutes (default 45).
* `env.nightlength` - Length of nighttime in minutes (default 15).
* `weather.ocean_level` - Adjust the sea level (default 0).
* `weather.rain` - Force rain amount (0-1).
* `weather.fog` - Force fog amount (0-1).
* `weather.wind` - Force wind amount (0-1).

**🚁 VEHICLE POPULATIONS (0 = Disabled)**
* `minicopter.population` - Natural minicopter spawns on roads (default 0).
* `scraptransporthelicopter.population` - Natural scrap heli spawns (default 0).
* `motorrowboat.population` - Boat spawns on coast (default 2).
* `rhib.population` - RHIB spawns on coast (default 1).
* `hotairballoon.population` - Balloon spawns (default 1).
* `horse.population` - Horse spawns (default 2).
* `submarineduo.population` - Duo sub spawns (default 1.5).
* `submarinesolo.population` - Solo sub spawns (default 1.5).
* `snowmobile.population` - Snowmobile spawns (default 1).
* `traincar.population` - Workcart spawns on tracks (default 1).

**🐻 ANIMAL POPULATIONS**
* `bear.population` (default 2)
* `boar.population` (default 5)
* `wolf.population` (default 2)
* `stag.population` (default 3)
* `chicken.population` (default 3)

**📦 EVENTS & LOOT**
* `hackablecrate.requiredhackseconds` - Seconds to unlock a locked crate (default 900 / 15 mins).
* `hackablecrate.decayseconds` - Seconds before an unlocked crate despawns (default 7200).
* `heli.lifetimeminutes` - How long the patrol heli stays before leaving (default 15).
* `heli.guns` - Enable/disable patrol heli guns (default 1).
* `heli.bulletDamageScale` - Patrol heli bullet damage multiplier (default 1).
* `bradley.respawndelayminutes` - Base minutes between Bradley APC spawns (default 60).
* `bradley.respawndelayvariance` - Variance in Bradley spawn time (default 1).
* `cargoship.event_enabled` - Enable/disable cargo ship event (default true).
* `patrolhelicopter.event_enabled` - Enable/disable patrol heli event (default true).

**🛠️ CRAFTING & BUILDING**
* `craft.instant` - Enable instant crafting for everyone (default false).
* `construct.frameminutes` - Minutes players have to demolish/rotate a placed building block (default 10).

**💬 CHAT & VOICE**
* `chat.enabled` - Enable/disable text chat (default true).
* `chat.serverlog` - Log chat to server console/logs (default true).
* `chat.historysize` - Number of chat messages kept in history (default 1000).
* `voice.loopback` - Hear your own voice (for testing, default false).

**🛡️ ANTI-HACK & SECURITY**
* `antihack.enforcementlevel` - 0 = no kicks, 1 = kick, 2 = ban (default 1).
* `antihack.maxviolation` - Violation threshold before kick/ban (default 100).
* `antihack.admincheat` - Allow admins to bypass antihack checks (default true).

**📱 COMPANION APP (RUST+)**
* `app.port` - The port used by the Rust+ companion app.
* `app.publicip` - The public IP used by the Rust+ companion app.

**🎄 SEASONAL EVENTS**
* `xmas.enabled` - Force enable Christmas event (default false).
* `halloween.enabled` - Force enable Halloween event (default false).
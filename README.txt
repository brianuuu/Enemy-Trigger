---------------------------Sonic Generations Mod--------------------------
-----------------------------Enemy Trigger v1.0---------------------------

This is a mod for Sonic Generations that enable events to destroy enemy and trigger events.

------------------------------------------------------------
Mod Usage
------------------------------------------------------------
This is NOT a standalone mod and does NOT modify stages in any way, user must add functionality to their own mod. This mod is setup as standalone so user can get updates from update server.

You are free to use the .dll file included, but you must include the following somewhere in your mod (e.g. README file):
-Credit brianuuu for the Enemy Trigger dll mod
-Link the source code from: https://github.com/brianuuu/DllMods/tree/master/Source/EnemyTrigger

You are also free to use the source code in your repository to add other dll codes for you own mod (since multiple dll files are not supported yet), you will still need to fullfill the conditions above.

There are two ways to use this in stages:
-Trigger events from destroying enemies: In EventSetter, set Trigger to 4 and add the list of enemies to TriggerList, this can be used for destroying a group of enemies to disable laser or enable pully etc.
-Use event to destroy enemy: In EventCollision/EventSetter, set Event to 12 and add the enemy to the respective TargetList, this can be used for destroying enemy by environmental objects like spikes or missiles etc.

-This mod works ONLY with HedgeModManager, SonicGMI is NOT supported!

------------------------------------------------------------
Credits
------------------------------------------------------------
brianuuu - Main Developer

# rAntiCheat v1.7

**This mod and it's code exists purely for inspiration now, the mod itself should not be used in a server.**

Advanced anticheat for Hide'n'Seek mod in CS 1.6. https://github.com/Ranarrr/rAntiCheat

**NB!!**
This uses the mdb Ban System. You can change the way bans are handled, so instead of amx_mban you would use amx_ban, but you need to change the parameters for the command.

# Includes:
- Strafe helper detections ( 8 methods )
- Simple bhop hack detections
- Some POC ( Proof Of Concept ) stuff
- FPS detection
- Checking standard cvars
- JumpBug checking (slow + speedhack)
- Detects simple strafe scripts
.. Exclude steamids

# How to exclude SteamIDs
Use rAntiCheat-exclude-steamid.
Create a file named "ex-SteamID.ini" in configs directory. Add 1 SteamID per line, will not work if you add multiple per line.
The SteamIDs added will be excluded from all detections.

# rRP ( rRecordPlayer ) / rSRP ( rStopRecordPlayer )
This is a function in the anticheat, which makes it possible to record every frame of a player.
This will output each frame in the format of, in a file in directory logs with filename of player.log:

( L DD/MM/YYYY - HH:mm:SS: sdmv(Sidemove): ### \t fwmv(Forwardmove): ### \t WASD \t DUCK \t JUMP \t Height_from_ground.00 \t Velocity.00 )

This can detect several things, like a bhop hack/macro, gstrafe hack/macro or an sgs hack/macro and etc.

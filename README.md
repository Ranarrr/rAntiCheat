# rAntiCheat v1.5

Advanced anticheat for Hide'n'Seek mod in CS 1.6. https://github.com/Ranarrr/rAntiCheat

# Includes:
- Strafe helper detections ( 8 methods )
- Simple bhop hack detections
- Some POC ( Proof Of Concept ) stuff
- FPS detection
- Checking standard cvars
- JumpBug checking (slow + speedhack)
- Detects simple strafe scripts
.. Exclude steamids

# rRP ( rRecordPlayer ) / rSRP ( rStopRecordPlayer )
This is a function in the anticheat, which makes it possible to record every frame of a player.
This will output each frame in the format of, in a file in directory logs with filename of player.log:

( L DD/MM/YYYY - HH:mm:SS: sdmv(Sidemove): ### \t fwmv(Forwardmove): ### \t WASD \t DUCK \t JUMP \t Height_from_ground.00 \t Velocity.00 )

This can detect several things, like a bhop hack/macro, gstrafe hack/macro or an sgs hack/macro and etc.

# Amxx files
- [http://rgho.st/download/private/6JrTDNTwR/5a9d74825a1798ec69014aa4523a731f/34be6968bed7c049554fd3b18262572fe9de5f22/rAntiCheat.rar](Normal rAntiCheat)
- [http://rgho.st/download/private/6Hvqn8c6Y/534cc9b089ed1557e827e81deb50f442/0ce97d09a4fd09c995b17dc91a97186885591941/rAnticheat-exclude-steamid.rar](rAntiCheat that excludes steamids)

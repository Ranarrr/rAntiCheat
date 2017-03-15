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

# rRP ( rRecordPlayer ) / rSRP ( rStopRecordPlayer )
This is a function in the anticheat, which makes it possible to record every frame of a player.
This will output each frame in the format of, in a file in directory logs with filename of player.log:

( L DD/MM/YYYY - HH:mm:SS: sdmv(Sidemove): ### \t fwmv(Forwardmove): ### \t WASD \t DUCK \t JUMP \t Height_from_ground.00 \t Velocity.00 )

This can detect several things, like a bhop hack/macro, gstrafe hack/macro or an sgs hack/macro and etc.
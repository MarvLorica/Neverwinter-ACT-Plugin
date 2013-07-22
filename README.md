Neverwinter-ACT-Plugin
======================

An plugin for ACT (Advanced Combat Tracker) to parse combat log file from Neverwinter by Perfect World.

- ACT is found at http://advancedcombattracker.com/
- D&D Neverwinter is found at http://nw.perfectworld.com/

This plugin is based on the version 0.0.5.1 plugin by Antday \<Unique\>, 
which is based on the STO plugin from Hilbert @ mancom, Pirye @ ucalegon.


State
=====
- Needs testing and verification.
- Tracking of CW Chaotic Growth gives the healing credit to the last CW to MM the target.
- I'm sure there are losts of different special cases left to handle.
- Combat log colored.
- Companion Pet's owners tracked.
- Damage base recording and effectiveness (dmg / dmgBase)
- Added 'Flank' (Combat Advantage?) as it's own column they way Critical Hits are.
- Removed Column types and features of ACT that are not used by the NW plugin.


Known Issues
============
- Devoted Cleric power "Flame Strike" causes falling damage that can not be tracked.  Falling damage does not specify who/what caused the fall.
- There is currently no way to detect zone changes from the Combatlog.Log file.
- All graphs show 10x the actual value.


Install
=======

- Download the Neverwinter.cs file to your computer.
- In the Neverwinter game use the command "/Combatlog 1" to begin logging to a file.  
- From ACT goto the plugins tab and "browse..." to and then enable the Neverwinter.cs plugin.  
- Goto the option tab now.   Select the Miscellaneous category and use the "Open log" button.  Select the file "C:\Users\Public\Games\Cryptic Studios\Neverwinter\Live\Logs\GameClient\Combatlog.Log".


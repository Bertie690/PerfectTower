# Scripts/Utilities for The Perfect Tower 2 

#### Quick Navigation
- [All-Purpose Ability Caster](#all-purpose-ability-caster)
- [Auto Restarter](#auto-restarter)
- [Accel Farm Locker](#accel-farm-locker)
- [Era Shield Disabler](#era-shield-disabler)

This is a repository for all my AI scripts and other useful stuff. 
Most of them don't require turbo exec to work and should not be run while turbo exec is running as it will either lag out or outright break most of the scripts listed here.

I try to make all my scripts (especially ones that activate on startup) as resilient and idiot-proof as possible by adding numerous checks to do things like stopping scripts from gaining additional copies on restart or preventing scripts that restart tower testing from interrupting an already-started run if you accidentally turn AI off and on again.

## All-Purpose Ability Caster
Ability caster that tries to cast every active module in the current blueprint one after the other, wrapping around once it hits the end. Works on any blueprint with any amount and combination of active modules, making it extremely versatile. Position based modules are being used at a random offset to the tower (adjustable by changing the PosOffset variable in line 1) to try and reduce overlap.

Script will skip to the next active module if the current one to be casted would be useless (like using Dispel without any debuffs) or shouldn't be spammed (examples include reboot, redirect, rak's curse, google's influence, etc). 

**Now comes in several different file sizes to accomodate players at all stages of progression!** 
The larger packages are faster at casting abilities (less downtime) but also have a higher line count, so use the largest version your RAM can support. 

### INSTRUCTIONS

Press 1 to start a copy of the script, press M to stop them all. Scripts will run indefinitely until M is pressed or tower testing is exited, and can only be started while actively in tower testing.

### IMPORT CODES

12 line:
[Tower Tester - 12 line.txt](https://github.com/Bertie690/PerfectTower/files/11746871/Tower.Tester.-.12.line.txt)

16 line:
[Tower Tester - 16 line.txt](https://github.com/Bertie690/PerfectTower/files/11746872/Tower.Tester.-.16.line.txt)

20 line:
[Tower Tester - 20 line.txt](https://github.com/Bertie690/PerfectTower/files/11746873/Tower.Tester.-.20.line.txt)

24 line: 
[Tower Tester - 24 line.txt](https://github.com/Bertie690/PerfectTower/files/11746874/Tower.Tester.-.24.line.txt)

## Accel Farm Locker
AI script to automate accel farming for getting to MT13. 
Initially disables Era Burst & Critical Wavejump softwares until you have enough xp to max out the era dividers (I arbitratily set this to 3M; feel free to change this as you wish), then turns them back on until you get to era 90B. Once there, it turns them back off again and waits until you get a lot of wave acceleration factor (80T by default) before re-enabling them and letting you go zoom. 

Only 15 lines long, so should be easy to afford by the time you get to mt12.

### IMPORT CODE
[Accel Farm Locker.txt](https://github.com/Bertie690/PerfectTower/files/11747462/Accel.Farm.Locker.txt)

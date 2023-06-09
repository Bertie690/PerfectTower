# Scripts/Utilities for The Perfect Tower 2 

#### Quick Navigation
- [All-Purpose Ability Caster](#all-purpose-ability-caster)
- [Auto Restarter](#auto-restarter)
- [Accel Farm Locker](#accel-farm-locker)

This is a repository for all my AI scripts and other useful stuff. 
Most of them don't require turno exec to work and should not be run while turbo exec is running as it will either outright break or lag out most of the scripts listed here.

## All-Purpose Ability Caster
Ability caster that tries to cast every active module in the current blueprint one after the other, wrapping around once it hits the end. Works on any blueprint with any amount and combination of active modules, making it extremely versatile. Position based modules are being used at a random offset to the tower (adjustable by changing the PosOffset variable in line 1) to try and reduce overlap.

Script will skip to the next active module if the current one to be casted would be useless (like using Dispel without any debuffs) or shouldn't be spammed (examples include reboot, redirect, rak's curse, google's influence, etc). 

**Now comes in several different file sizes to accomodate players at all stages of progression!** 
The larger packages are faster at casting abilities (less downtime) but also have a higher line count, so use the largest version your RAM can support.  

### INSTRUCTIONS

Press 1 to start a copy of the script, press M to stop them all. Scripts will run indefinitely until M is pressed or tower testing is exited, and can only be started while actively in tower testing.

(It will also stop my other 2 tower testing scripts when it stops itself; feel free to delete the last 2 lines if you don't plan on using either one.)

### IMPORT CODES

12 line:
```
[Tower Tester - 12 line.txt](https://github.com/Bertie690/PerfectTower/files/11708627/Tower.Tester.-.12.line.txt)
```

16 line:
```
[Tower Tester - 16 line.txt](https://github.com/Bertie690/PerfectTower/files/11708632/Tower.Tester.-.16.line.txt)

```

20 line:
```
[Tower Tester - 20 line.txt](https://github.com/Bertie690/PerfectTower/files/11708636/Tower.Tester.-.20.line.txt)
```

24 line: 
```
[Tower Tester - 24 line.txt](https://github.com/Bertie690/PerfectTower/files/11708638/Tower.Tester.-.24.line.txt)
```

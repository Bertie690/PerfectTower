# PerfectTower

#### Quick Navigation
- [All-Purpose Ability Caster](#all-purpose-ability-caster)
- [Auto Restarter](#auto-restarter)
- [Accel Farm Locker](#accel-farm-locker)

This is a repository for all my AI scripts and other useful stuff. 
Most of them don't require turno exec to work and should not be run while turbo exec is running as it will either outright break or lag out most of the scripts listed here.

## All-Purpose Ability Caster
Ability caster that tries to cast every active module in the current blueprint one after the other, wrapping around once it hits the end. Works on any blueprint with any amount and combination of active modules, making it extremely versatile. Position based modules are being used at a random offset to the tower (adjustable by changing the PosOffset variable in line 1) to try and reduce overlap.
(It also automatically upgrades the era dividers if you're in era as an added bonus.)

Script will skip to the next active module if the current one to be casted would be useless (like using Dispel without any debuffs) or shouldn't be spammed (examples include reboot, redirect, rak's curse, google's influence, etc). 

**Now comes in several different file sizes to accomodate players at all stages of progression!** 
The larger packages are faster at casting abilities (less downtime) but also have a higher line count, so use the largest version your RAM can support.  

### INSTRUCTIONS

Press 1 to start a copy of the script, press M to stop them all. Scripts will run indefinitely until M is pressed or tower testing is exited, and can only be started while actively in tower testing.

(It will also stop my other 2 tower testing scripts when it stops itself; feel free to delete the last 2 lines if you don't plan on using either one.)

### IMPORT CODES

13 line:
```
_____
```

17 line:
```
_____
```

21 line:
```
_____
```

25 line: 
```
_____
```

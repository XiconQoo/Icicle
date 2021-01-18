# Icicle TBC Addon (forked from Schaka)

### [v1.3.2-Beta Download Here](https://github.com/XiconQoo/Icicle/releases/download/v1.3.2-Beta/Icicle_XiconEdit_v1.3.2-Beta.zip)

This addon shows enemy CDs on their nameplates.

This is a slightly improved version of (https://github.com/Schaka/Icicle).
The goal is to make it more reliant on clearing it's own icons.

You can create testicons with `/icicletest` on all visible plates.

You can reset all active cooldown with `/iciclereset`.

This is compatible with 
- https://github.com/XiconQoo/XiconPlateBuffs
- https://github.com/sativahigh/SoHighPlates
- https://github.com/shagu/ShaguPlates/
- Aloft

## Screenshot

![Screenshot](../readme-media/sample.png)

### Changes

v1.3.2
- change `/icicletest unitname` to `/icicletest` - now shows cooldowns on all visible nameplates
- add `/iciclereset` to reset all active cooldown (helpful for duels for instance)

v1.3.1
- add ElvUI support

v1.3
- SoHighPlates support to frame.oldname:GetText() (more reliant)

v1.2
- add icon sort option by time (none, ascending, descending)

v1.1-Beta
- add XiconPlateBuffs and SoHighPlates support
- fixes icons suddenly appearing
- add testmode
- code formatting fixed

### TODO

- icon creation module rewrite, to reuse iconframes instead of creating more and more (less memory usage)
- filter cooldowns
- add cooldowns
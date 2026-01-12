# Dark Mode For AHK-v2 ([AutoHotkey](https://github.com/AutoHotkey/AutoHotkey))

This is an AutoHotkey "scriptlet" for applying a dark theme to AHK GUIs via the Win32 API. It was originally created by [jNizM](https://www.autohotkey.com/boards/memberlist.php?mode=viewprofile&u=75) (available [here](https://www.autohotkey.com/boards/viewtopic.php?t=115952)) and then revised by pikakid98.

The relevant file is [DarkMode.ahk](DarkMode.ahk), and is intended as the target of an [`#Include`](https://www.autohotkey.com/docs/v2/lib/_Include.htm) directive.

If you're confused, an example script is provided, which can be ran as-is or can be compiled.

## Requirements for compiling the example script

* [Ahk2Exe](https://github.com/AutoHotkey/Ahk2Exe)
* [Upx](https://github.com/upx/upx)

#### Additional requirement if [Compile-in-ator](https://github.com/pikakid98/Compile-in-ator) is used for compiling the example script

* An environment variable named `AHK` set to your AutoHotkey path; e.g. `C:\Program Files\AutoHotkey\v2`
RoboLauncher
==============

RoboLauncher is a tool to quickly find and run commands and scripts. Similar to [Raycast](https://www.raycast.com) or OSX's Spotlight Search.
Based on a fork of Mark Record's `ScriptLauncher`.
The RoboLauncher is more focused on being an all-around RoboFont command palette.

Usage:
------

**For the time being, place the `main.py` in your RoboFont scripts folder and run the 'Update Menu' in the scripts' dropdown.**

Open the window using `Command + backslash`.
Run selected script using `return`

Advanced
--------

### Opening Script in the RoboFont Script Window

Open a selected script using `Command + return`.

### Shortcuts

View all RoboFont shortcuts by typing "shortcuts".
This is a read-only function to let you see all the shortcuts being used.

### Preferences

Open preferences by typing "preferences", or using `Option + Command + comma`.
Preferences will be opened in an external text editor as an `.ini` file. 
Changes will take affect once you run RoboLauncher again

-   ### Scripts/Extensions

    If you use custom locations for Scripts and Extensions, you can set
    the path here.

-   ### Text Editor

    You can either use your prefered external text editor or the RoboFont default
    when opening python scripts from within RoboLauncher.
    values can be either `robofont` or `external`. This settings is *not* case-senstive.

-   ### Search Near Open Fonts for Scripts

    ScriptLauncher will look for scripts located near your fonts. This
    is helpful if you keep project-based scripts near your fonts. The
    default is to move up 3 directories and start searching from there.
    **CAUTION:** Expanding the search area too much will cause the
    script to run slowly. You might need to fiddle with the Search Up
    setting to find the setting that works best for you.

-   ### Rememember Last Scripts

    The number of script that show up in the window.

Acknowledgements
----------------

-   Thanks to Mark Record for writing ScriptLauncher in the first place!        

-   Thanks to [Tal Leming](https://www.typesupply.com/) for help with
    the advanced parts (StatusInteractivePopUpWindow!), and sharing the
    name ScriptLauncher.

-   Thank you to my friends and coworkers at [Commercial
    Type](https://commercialtype.com).

-   And thank you to [David Jonathan Ross](https://www.djr.com/) for
    testing and feedback.

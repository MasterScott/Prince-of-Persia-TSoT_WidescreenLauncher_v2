### Prince of Persia: The Sands of Time ~ Widescreen Launcher v2

This *PoP TSoT* launcher is based on **[UniGame Launcher v1.4.7](https://github.com/alex47exe/UniGame-Launcher/releases/tag/v1.4.7)** and **nemesis2000**'s **widescreen fix** at [http://ps2wide.net](http://ps2wide.net/pc.html#popst), already included

------

***Features:***

- game will run on the first cpu core, to avoid extreme gameplay speed on multi-core cpus
- automatically detects resolution and modifies it to *pop.ini*
- when *POP.exe* runs the first time, *Hardware.ini* gets reset to some default values, causing some graphical issues when fog is enabled; to avoid this, launcher uses *blank.exe* instead of *POP.exe* at first run, then it automatically corrects those values and launches the game
- launcher runs as administrator only at first launch, if `run_admin = 1` in *ini* file

------

***Requirements:***

1. Prince of Persia: The Sands of Time - any version

------


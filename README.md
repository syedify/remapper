#REMAPPER 
##Remaps the keys on a target computer.


##LICENSE:
Remapper, Copyright (C) 2016  Syed Huq and Mishaal Al Bashir. Remapper comes with ABSOLUTELY NO WARRANTY.
This is free software, and you are welcome to redistribute it under certain conditions.

This program is free software; you can redistribute it and/or modify it under the terms 
of the GNU General Public License as published by the Free Software Foundation; either 
version 3 of the License, or (at your option) any later version.

##INSTALLATION:
* Download AutoHotkey from "https://autohotkey.com/docs/Tutorial.htm#s11" VERSION AutoHotkey_1.1.24.03_setup
* Copy the installation folder into ../remap/
* Run setup.bat and install the AutoHotkey installer.

##USAGE: 
* Open remap.bat in text editor
* Set the value of REPEAT_INTERVAL to be the number of seconds you want the script to repeat 
* Set the value of REMAP_INTERVAL to be the duration of remapping event in seconds
* Set the value of KEEP_RUNNING to run the script indefinitely (Probably set to 1)
* Save
* Drag the files into startup folder of target PC 

##TERMINATION:
* Open task manager
* Find cmd.exe process and end process
* Find AutoHotKey.exe process and end process


##INCLUDED FILES:
* map.ahk
* remap.bat
* enter.ahk

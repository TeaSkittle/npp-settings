# npp-settings
![theme.PNG](theme.PNG)

## Overview
I have created these settings because at my job I can not use emacs on the windows machines, but Notepad++ is installed! So I went out of my way to try and recreate as much of my emacs setup in Notepad++, and this is the result of that.

## cyber.xml
A slightly edited version of the twilight theme, inspired by this emacs theme: [cyberpunk-theme.el](https://github.com/n3mo/cyberpunk-theme.el). Only tested to work with batch, powerscript, and perl files.

## shortcuts.xml
These are my keybinding with various macros, I tried to have the basic editing feel of emacs. Obviously can't replicate emacs in Notepad++, but this has a similar feel for the simple text editing controls. Here are the binds I have set/changed(everything else has been left to default):
* C-f	Move forward
* C-b	Move backward
* C-n	Next line
* C-p	Previous line
* M->	Go to end of file
* M-<	Go to start of file
* C-d	Delete character
* C-k	Delete line
* C-r	Search
* M-g	Go to line	

## Installation
* Place shortcuts.xml in %AppData%\Notepad++
* Place cyber.xml in C:\Program Files (x86)\Notepad++\themes
* In Notepad++:
  * Settings -> Style Configurator -> Select theme

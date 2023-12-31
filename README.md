Cat Compare
================
This package adds a simple comparison tool (ported for new st4) to Sublime Text 3 and 4.

![Screenshot](https://dougty.com/files/SBSCompareScreenshot5.png)

Features
---
  - Normal theme load (in the old source this works weakly on new versions of sublime)
  - Easily select two tabs or selections to compare
  - Comparison results open in a new window
  - Empty lines added so common code lines up
  - Count number of lines changed
  - Highlighting of changed lines
  - Intra-line diff highlighting
  - Synchronized scrolling

Installation Options
---
  - Search for and install using [Package Control](https://sublime.wbond.net/installation) (ctrl+shift+P, "Install Package")
  - Clone or extract this repo to a new folder in your Sublime 'Packages' folder  
    (*Preferences -> Browse Packages*)

Usage Options
---
  - Right click on a tab and select "Compare with..."
  - Right click somewhere in the active view and select "Compare with..."
  - Right click on a tab and select "Compare with active tab"
  - Highlight text, right click -> "Mark selection for comparison"
   - Mark a second selection, then right click -> "Compare selections"
  - Create two selections by holding CTRL, then "Compare selections"
  - From the command line: [see README_COMMANDS.md](README_COMMANDS.md)
  - Jump to next: `Alt+N`, Jump to previous: `Alt+P`
  
Configuration
---
  - Highlight colours and other options can be configured in SBSCompare.sublime-settings
  - Hotkeys can be changed in the included `Default (PLATFORM).sublime-keys` files
  - To access: *Preferences -> Package Settings -> Cat Compare*

License & Contributing
---
 - [Apache 2.0 license](LICENSE)
 - Pull requests welcome!

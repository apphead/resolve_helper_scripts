# Davinci Resolve Helper Scripts

Library for various tools created with Davinci Resolve scripting API.
GUI made with PySimpleGUI, which is easier GUI solution for new programmers.

The main goal of this library, beside my learning to program, is to help keep a Resolve project tidy and save some boring repetitive labor.

# Credits
-  [Qiang Tang](https://github.com/veryqiang) for his foundational implementation of pysimplegui in Davinci Resolve

# Scripts:

- importer.py:  for importing a folder containing sub-folders and footages to Davinci Resolve.
    * tagging/timestamp for folder names
    * clip color
    * marker labels
    * create timeline from imported clips (optional). Useful for VFX review sessions.

## How to install:
Make sure you have Python 3.6 or newer installed. Open command and navigate to you python installation directory e.g. C:\Python311\

Then install PySimpleGUI:
    
    pip install pysimplegui
or

    pip3 install pysimplegui

Then copy the script to %APPDATA%\Blackmagic Design\DaVinci Resolve\Support\Fusion\Scripts\[targetDir]
    [targetDir] is a subfolder. Have not quite figured out how it affects appearance in the script menu yet. [TODO]

## Run the script:
 
    python3 ./resolve_importer.py
    
Optionally you can config Python Launcher 3.6+ as default method for .py files then you can click and run the script directly.

Tested on macOS Catalina. 


Note: 
I am a colorist new to programming, this is my learning project. 
Though the tool should not be destructive, please test in your non-production environment.

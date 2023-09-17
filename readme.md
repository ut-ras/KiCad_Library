# RAS KiCAD Library
This repository contains KiCAD symbols, footprints, and 3D models for our PCBs

# Using this repository
This repository should be contained as a submodule in a KiCAD project.  
When cloning a repo that uses this library, use `git clone [your link] --recursive` otherwise the submodule won't be cloned.
To add this library to your repository use the command `git submodule add git@github.com:ut-ras/KiCad_Library.git` or `git submodule add https://github.com/ut-ras/KiCad_Library.git` depending on whether or not you use SSH or HTTP to clone.

Once in your KiCAD project, go to the schematic editor, `Preferences` -> `Manage Symbol Libraries` -> `Project Specific Libraries` then add each symbol file into the table.

# Adding to this repository
Since this library will be stored as a submodule in your library, it acts as any github repository. During the development of your board if you find any symbols or footprints then add them to this library so others can also use them.  
First create a branch in this library for your repository, push any changes as you make them, and once your board is done make a Pull Request to merge your changes to main

# Rules
1) Any symbol added should have an associated footprint, datasheet, part number, and 3D model
2) Don't commit directly to the main branch
3) Keep the repository organized (connector footprints should be in connectors.pretty etc)
4) Have fun!
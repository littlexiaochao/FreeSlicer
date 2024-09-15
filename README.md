# Introduction

FreeSlicer is a 3D printing plugin in Grasshopper. Designers can draw or generate curves and then convert them into Gcode directly. FreeSlicer focuses on the flexible textiles generation by 3D printing, and also suitable to the general 3D printing.

Grasshopper is a built-in plugin for Rhino. The download address: https://www.rhino3d.com/download/.

# FreeSlicer Install

1. Open Rhino and open Grasshopper.
2. In Grasshopper, click "File" -> "Special Folders" -> "User Object Folder".
3. Take "FreeSlicer_v2" folder into "UseObjects" folder.
4. Restart the Rhino software to use the plug-in in Grasshopper

![image](https://github.com/littlexiaochao/FreeSlicer/blob/main/plugin_guide.png)

It is recommended to use FreeSlicer on a Windows system. If you are using Rhino on macOS, the folder address format when saving the Gcode will be different from the one shown in the image. Use the macOS folder address format, for example: /Users/FreeSlicer/Documents/gcode. Additionally, you need to add a “/” at the end of the path, i.e.: /Users/FreeSlicer/Documents/gcode/.

# User Interface

For beginners, we also provide a user interface through the Human UI plugin, before using the user interface (Interface.gh), you need to confirm whether you have installed the Human UI plugin in Grasshopper.
Plugin download address: https://www.food4rhino.com/en/app/human-ui

![image](https://github.com/littlexiaochao/FreeSlicer/blob/main/user_interface_guide1.jpg)

![image](https://github.com/littlexiaochao/FreeSlicer/blob/main/user_interface_guide2.jpg)

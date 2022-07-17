# Addon Type

I've put a little bit here to explain the directory layout of this addon.  
As you can't just place this within the FreeCad Mod directory but instead it needs to be installed via pip.

Currently Freecad has multiple ways to install Addons or Workbenches (Gui Addons).  
Older style addons would place themselves within a Mod subdirectory within FreeCad.

Under Windows typically this would live within

  * `C:\Program Files\FreeCAD 0.20\Mod`
    Addons bundled within FreeCad
  * `C:\Users\<username>\AppData\Roaming\FreeCAD\Mod`
    Addons installed via the Addon Manager

The newer style addons can instead be installed via pip within the FreeCad install.
Using pip to manage the install of the addon with a different directory layout

  * https://forum.freecadweb.org/viewtopic.php?t=36051
  * https://github.com/FreeCAD/freecad.workbench_starterkit


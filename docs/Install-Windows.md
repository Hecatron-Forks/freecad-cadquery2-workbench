# Installation - Windows

## Installing CadQuery

The first step is to install cadquery.  
For this we're going to use the new pip method which avoids the need for conda.
```sh
cd "C:\Program Files\FreeCAD 0.20\bin"
"C:\Program Files\FreeCAD 0.20\bin\python" -m pip install cadquery==2.2.0b0
```

Typically any python packages that come pre-bundled with Freecad
are located within `C:\Program Files\FreeCAD 0.20\bin\Lib\site-packages`

Any packages we install manually ourselves typically end up under
`C:\Users\<username>\AppData\Roaming\Python\Python38\site-packages\cadquery`


## Installing The Addon

Next we need to install the cadquery addon
```sh
cd "C:\Program Files\FreeCAD 0.20\bin"
"C:\Program Files\FreeCAD 0.20\bin\python" -m pip install git+https://github.com/jpmlt/freecad-cadquery2-workbench.git@master
```

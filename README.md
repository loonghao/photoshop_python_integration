photoshop_python_integration
============================

Python interpreter for Photoshop integration.

![demo](https://i.imgur.com/25TrzbV.gif)

Installing
----------
- Download [photoshop_python_integration](https://drive.google.com/drive/folders/1jPFud2KU9zulrTlldU7MyxfFN9iaRHQE?usp=sharing) and unzip the installation package.

- If your photoshop has another version installed or it is installed in another
 location please modify `site.jsx`.
![set python path](https://i.imgur.com/xRmquQf.png)

- Copy `photoshop_python_integration` from this root folder to the 
`Presets\Scripts` folder under your photoshop installation directory.

For example:

`C:\Program Files\Adobe\Adobe Photoshop 2020\Presets\Scripts`

Reopen Photoshop under the `Filter` menu to see the two menus of `python` and `pythonIDE`. 
Enjoy ~

![menu](https://i.imgur.com/2IFyzwc.png)

Need to implement
-----------------
- Use the CI build installer.

Integration
===========

- [multi_script_editor](https://github.com/paulwinex/pw_MultiScriptEditor)
This is a cross application, cross platform and open source Python editor, 
which can be run as a standalone application or embedded in another 
application. The main purpose for integration - the ability to script in Python.

- [photoshop_python_api](https://github.com/loonghao/photoshop-python-api)
Python API for Photoshop.

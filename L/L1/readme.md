# Install python, jupyterlab and create a jupyterlab shortcut

## Install python 
Download the latest version for windows and follow the instruction for installation 
https://www.python.org/downloads/

Note: Make sure you select the right system type (32-bit or 64-bit). If you do not know: Use the search icon near `Start Menu` and search for `About` that will take you to`Settings`: `About` where you can know if you have a 32-bit or 64-bit processor. 

## Install JupyterLab 
Follow these instructions for installing jupyter lab: https://jupyter.org/install   
Jupyter Lab is an open-source interactive development environment that facilitates data science and scientific computing in Python through a web-based interface

## Create a shortcut for your jupyterlab
Right click the windows screen: `New` > `Shortcut`  
Type the location of the item: “cmd.exe” then click next  
Type a name for this shortcut: ”JupyterLab” or any name you like and click finish   
Right click on shortcut: `Properties`: `Target`   

At the target cell write down the following: 
`` cmd.exe /k "cd C:\Users\aelshall\" & jupyter lab && exit ``

Note 1: You need to replace “aelshall” with your username on your machine.

Note 2: “C:\Users\aelshall “ is the location where you want your jupyterlab to access in your file system.

In case you are wondering:
cmd.exe is a Command Prompt to execute MS-DOS commands 
The /k switch tells Command Prompt to issue the command that follows, and then stay open
"cd C:\Users\your_username_here\" will go the the specified path 
& to add another command
jupyter lab will launch the app
&& to add another command that is exit 

## Change shortcut icon (optional)
Download this icon and save it anywhere you like
 https://github.com/aselshall/git-tutorial-/blob/master/JupyterLab-icon.ico
If you do not like this icon, get any other icon that you like that has the extension `.ico`

Right click on the shortcut: `Change Icon`: `Browse`: Select the icon from where you saved it.


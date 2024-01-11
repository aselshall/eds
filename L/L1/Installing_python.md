# Installing python and jupyterlab and creating a jupyterlab shortcut for Windows

In this course we will use python with [jupyterlab](https://jupyter.org/), which is an open-source interactive development environment that facilitates data science and scientific computing in python through a web-based interface.  
   
Installing python using [anaconda](https://docs.anaconda.com/free/anaconda/install/index.html) provides a streamlined and comprehensive approach, bundling not only python but also popular data science libraries and tools. It simplifies the setup process, ensuring compatibility among packages. On the other hand, installing python and jupyterlab manually allows for more control over specific versions but requires additional effort in managing dependencies and configurations. [This video](https://youtu.be/ozTSqhU9Hek?si=cGzNRATmPOPsoLCg) for example shows how to install python with anaconda, the different tools that anaconda provides, how to create a shortcut for jupyterl lab, and how to get started.    
  
If you cannot install anaconda on your machine, [FGCU appsanywhere](https://www.fgcu.edu/its/appsanywhere/) has anaconda. However, some features such as adding a jupyterlab extension will be disabled.
   
Alternatively, you can manually install python and jupyterlab following theses instructions. 

## Install python 
Download the latest version for windows and follow the instruction for installation 
https://www.python.org/downloads/

Note: Make sure you select the right system type (32-bit or 64-bit). If you do not know: Use the search icon near `Start Menu` and search for `About` that will take you to`Settings`: `About` where you can know if you have a 32-bit or 64-bit processor. 

If you need help you can check out this [video](https://youtu.be/LQ47rIO5bTw?si=FHA1B0j0uZIn62La) or something similar.

## Install jupyterlab 
Follow these instructions for installing jupyter lab: https://jupyter.org/install   

To run jupyterlab open Command Prompt and type 
````
python -m jupyter lab 
````
In case you are wondering, to open Command Prompt go to search near to windows `Start` menu and type `cmd`. 
  
If you want jupyterlab to start at a different path, on the Command Prompt you need to first to go to this path. Here is an example,
````
cd /d C:\Users\aelshall
````
Note the `/d` switch tells the command prompt to change the directory and the drive and `cd` specifies the target directory. 
   
Then you can start the jupyterlab as shown above, but this is tedious, so it is easier to create a shortcut that starts jupyterlab for you. 

## Create jupyterlab shortcut
Right click the windows screen: `New` > `Shortcut`  
Type the location of the item: `cmd.exe` then click next  
Type a name for this shortcut: "JupyterLab" or any name you like and click finish   
Right click on shortcut: `Properties`: `Target`   

At the target cell write down the following: 
```` 
cmd.exe /k "cd C:\Users\aelshall\" & jupyter lab && exit 
````
Note 1: You need to replace “aelshall” with your username on your machine.  
Note 2: “C:\Users\aelshall “ is the location where you want your jupyterlab to access in your file system.  

In case you are wondering:
- `cmd.exe` is a Command Prompt to execute MS-DOS commands 
- The `/k` switch tells Command Prompt to issue the command that follows, and then stay open
- `"cd C:\Users\aelshall\"` will go the the specified path 
- `&` to add another command
- `jupyter lab` will launch the app
- `&&` to add another command that is `exit`

Note if you installed jupyterlab through anaconda, use an anaconda prompt and at the target cell write down `jupyter lab && exit` as shown in [this video](https://youtu.be/ozTSqhU9Hek?si=cGzNRATmPOPsoLCg). 


## Change jupyterlab shortcut icon (optional)
Download this [jupterlab icon](https://github.com/aselshall/git-tutorial-/blob/master/JupyterLab-icon.ico) and save it anywhere you like.    
If you do not like this icon, get any other icon that you like that has the extension `.ico`  
   
Right click on the shortcut: `Change Icon`: `Browse`: Select the icon from where you saved it.


# Installing Python and Jupyterlab and creating a Jupyterlab shortcut for Windows

In this course we will use Python with [Jupyterlab](https://jupyter.org/), which is an open-source interactive development environment that facilitates data science and scientific computing in Python through a web-based interface.  

You can install Python using different methods:
- Anaconda: Installing Python using [anaconda](https://docs.anaconda.com/free/anaconda/install/index.html) provides a streamlined and comprehensive approach, bundling not only Python but also popular data science libraries and tools.
   - Pros: It simplifies the setup process, ensuring compatibility among packages.
   - Cons: Too much time and too much space needed and you will get a lot of tools that you will not use for this course
- Miniconda:  
   - Pros: Light weight version of Anaconda
   - Cons: You would need to do few extra things to use Jupterlab as shown in the document
- Installing Python manually 
   - Pros: Allows for more control over specific versions
   - Cons: Requires additional effort in managing dependencies and configurations
- FGCU AppsAnywhere (not recommended):  If you cannot install Python on your machine, [FGCU appsanywhere](https://www.fgcu.edu/its/appsanywhere/) has Anaconda.
     - Pros: You do not need to install anything and you can use Jupyterlab on the cloud
     - Cons: Many features such as adding a Jupyterlab extension will be disabled, old version of Python 3.8x, can creat problematic synic issue with OneDrive, etc. 
   
## Install Python 

### Install Python with Anaconda (not very much recommended)
[This video](https://youtu.be/ozTSqhU9Hek?si=cGzNRATmPOPsoLCg) for example shows how to install Python with Anaconda, the different tools that Anaconda provides, how to create a shortcut for jupyterl lab, and how to get started.
  
### Install Python with Miniconda (recommended)
You can easily install Python through Minoconda from [Minconda webpage](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html). You can find more information at [GeoPython - Installing Python](https://geo-Python-site.readthedocs.io/en/latest/course-info/installing-miniconda.html). 
   
### Install Python manually (not very much recommended)
Download the latest version for windows and follow the instruction for installation 
https://www.Python.org/downloads/

Note: Make sure you select the right system type (32-bit or 64-bit). If you do not know: Use the search icon near `Start Menu` and search for `About` that will take you to`Settings`: `About` where you can know if you have a 32-bit or 64-bit processor. 

If you need help you can check out this [video](https://youtu.be/LQ47rIO5bTw?si=FHA1B0j0uZIn62La) or something similar.

## Install Jupyterlab 
Follow these instructions for installing jupyter lab: https://jupyter.org/install   

## Run Jupyterlab

### For Python with Miniconda and Anaconda

Open an Anaconda Prompt and type `jupyter lab`

### For Python with manual installation

To run Jupyterlab open Command Prompt and type 
````
Python -m jupyter lab 
````
In case you are wondering, to open Command Prompt go to search near to windows `Start` menu and type `cmd`. 
  
If you want Jupyterlab to start at a different path, on the Command Prompt you need to first to go to this path. Here is an example,
````
cd /d C:\Users\aelshall
````
Note the `/d` switch tells the command prompt to change the directory and the drive and `cd` specifies the target directory. 
   
Then you can start the Jupyterlab as shown above, but this is tedious, so it is easier to create a shortcut that starts Jupyterlab for you. 

## Create Jupyterlab shortcut

### For Python with Anaconda and Miniconda 
If you installed Jupyterlab through Anaconda or miniconda, create an Anaconda prompt shortcut and at the target cell write down `jupyter lab && exit` for Anaconda or ` & jupyter lab && exit` for Miniconda as shown in [this video](https://youtu.be/ozTSqhU9Hek?si=cGzNRATmPOPsoLCg). 

### For Python with manual installation  
Right click the windows screen: `New` > `Shortcut`  
Type the location of the item: `cmd.exe` then click next  
Type a name for this shortcut: "Jupyterlab" or any name you like and click finish   
Right click on shortcut: `Properties`: `Target`   

At the target cell write down the following: 
```` 
cmd.exe /K "cd C:\Users\aelshall\" & jupyter lab && exit
````
**Note 1**: You need to replace “aelshall” with your username on your machine.  
**Note 2**: “C:\Users\aelshall “ is the location where you want your Jupyterlab to access in your file system and you can change this as you want.

In case you are wondering:
- `cmd.exe` is a Command Prompt to execute MS-DOS commands 
- The `/k` switch tells Command Prompt to issue the command that follows, and then stay open
- `"cd C:\Users\aelshall\"` will go the the specified path 
- `&` to add another command
- `jupyter lab` will launch the app
- `&&` to add another command that is `exit`

  
## Change Jupyterlab shortcut icon (optional)
Download this [jupterlab icon](https://github.com/aselshall/git-tutorial-/blob/master/JupyterLab-icon.ico) and save it anywhere you like.    
If you do not like this icon, get any other icon that you like that has the extension `.ico`  
   
Right click on the shortcut: `Change Icon`: `Browse`: Select the icon from where you saved it.


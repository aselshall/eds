# Installing Python and JupyterLab

## Overivew 
In this course we will use Python with [Jupyterlab](https://jupyter.org/), which is an open-source interactive development environment that facilitates data science and scientific computing in Python through a web-based interface.  

You can install Python using different methods:
- Anaconda (*not very much recommended*):  
Installing Python using [anaconda](https://docs.anaconda.com/free/anaconda/install/index.html) provides a streamlined and comprehensive approach, bundling not only Python but also popular data science libraries and tools. [This video](https://youtu.be/ozTSqhU9Hek?si=cGzNRATmPOPsoLCg) for example shows how to install Python with Anaconda, the different tools that Anaconda provides, how to create a shortcut for jupyterl lab, and how to get started.
   - Pros: It simplifies the setup process, ensuring compatibility among packages.
   - Cons: Too much time and too much space needed and you will get a lot of tools that you will not use for this course
- Miniconda (*recommended*):  
   - Pros: Light weight version of Anaconda
   - Cons: You would need to do few extra steps as shown in this tutorial
- Installing Python manually (*not recommended*):
   - Pros: Allows for more control over specific versions
   - Cons: Requires much additional effort in managing dependencies and configurations
- FGCU AppsAnywhere (*not recommended*):  
If you cannot install Python on your machine, [FGCU appsanywhere](https://www.fgcu.edu/its/appsanywhere/) has Anaconda.
     - Pros: You do not need to install anything and you can use Jupyterlab on the cloud
     - Cons: Many features such as adding a Jupyterlab extension will be disabled, old version of Python 3.8x, can creat problematic synic issue with OneDrive, etc. 

This tutorial shows you how to: 
- install Miniconda that will install Python for you
- use Miniconda to install JupyterLab
- create a JupyterLab shortcut 

## Installing Python and JupyterLab

### 1. Install Python with Miniconda

You can easily install Python through Minoconda from [Minconda webpage](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html). You can find more information at [GeoPython - Installing Python](https://geo-Python-site.readthedocs.io/en/latest/course-info/installing-miniconda.html). 

After the installation is complete, from Windows Star Menu, open Anaconda Prompt(Miniconda3) and type:
```code
python -- version
```
This will return to you the Python version that you have installed (e.g., Python 3.11.5). 

**Note:** Make sure you that you have a 64-bit system. If you do not know: Use the search icon near `Start Menu` and search for `About` that will take you to`Settings`: `About` where you can know if you have a 32-bit or 64-bit processor. 

### 2. Install and run Jupyterlab 
You do not want to use Python in a back screen, so you need to install a graphical user interface(GUI). For programming languages, a GUI is called interactive development environment (IDE). The IDE that we will use for this course is [Jupyterlab](https://jupyter.org/), which is an open-source IDE for Python, Julia, R, MATLAB/Octave, and few other programming languages. 
  
In Python, we generally use `pip` or `conda` for installation. For JupyterLab installation details you can check the [JupyterLab documentation](https://jupyter.org/install), or follow these steps:

Open your Anaconda Prompt(Miniconda3) from the Windows Start menu and install JupyterLab with pip by running this command:
```code
pip install jupyterlab
```
Alternatively, you can install JupyterLab with conda with conda-forge channel by running this command:
```code
conda install -c conda-forge jupyterlab
```

Once installed, launch JupyterLab with:
```code
jupyter lab
```

### 3. Create Jupyterlab shortcut
Each time you use JupterLab you do not want to open an Anaconda Prompt(Miniconda3) and type `jupyter lab`, so you can create a shortcut to automatically lunch JupyterLab. Here are the steps

**Create Anaconda Prompt Shortcut:** Drag Anaconda Prompt(Miniconda3) from Start Menu to Desktop, which will create an Anaconda Prompt(Miniconda3) shortcut. You can check that by clicking on it and then typing `jupyter lab` which will lunch JupyterLab.

**Customize Anaconda Prompt Shortcut:** To customize the shortcut to lunch JupyterLab automatically, right click on your shortcut and select "Properties". Then at the end of the "Target" cell type
```code
& jupyter lab && exit
```
At my machine the content of the "Target" cell now looks something like this:
```
%windir%\System32\cmd.exe "/K" C:\Users\username\AppData\Local\miniconda3\Scripts\activate.bat C:\Users\username\AppData\Local\miniconda3 & jupyter lab && exit
```
If this is unclear, check this [YouTube video](https://youtu.be/ozTSqhU9Hek?si=cGzNRATmPOPsoLCg). 
  
### 4. Change JupyterLab shortcut icon (optional)
In case you want your icon to look nice
- Download this [jupterlab icon](https://github.com/aselshall/git-tutorial-/blob/master/JupyterLab-icon.ico) and save it anywhere you like.
- If you do not like this icon, get any other icon that you like that has the extension `.ico`.
- Right click on the shortcut: "Change Icon": "Browse": Select the icon from where you saved it.
- You can now drag your icon from Desktop to Taskbar to make your JupyterLab handy.

## Next steps
Now you have JupyterLab and Python installed , you can start with these two links: [Getting Started with Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html) and [Getting Started with Python](https://foundations.projectpythia.org/foundations/getting-started-python.html)

# [Installing Python and JupyterLab](https://aselshall.github.io/eds/L/L1/installing_python)

## Tutorial
To install Python, JupyterLab, and the packages for the Environmental Data Science course read the instructions below  or watch the video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/DpgD-i29hKs?si=vVOpHqvkJfOlAfkE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Overivew 
In this course we will use Python with [Jupyterlab](https://jupyter.org/), which is an open-source interactive development environment (IDE) that facilitates data science and scientific computing in Python through a web-based interface.  

You can install Python using different methods:
- Miniconda (*recommended*):  
   - Pros: Light weight version (of Anaconda)
   - Cons: You would need to do few extra steps as shown in this tutorial
- Anaconda (*not very much recommended*):  
Installing Python using [anaconda](https://docs.anaconda.com/free/anaconda/install/index.html) provides a streamlined and comprehensive approach, bundling not only Python but also popular data science libraries and tools. [This video](https://youtu.be/ozTSqhU9Hek?si=cGzNRATmPOPsoLCg) for example shows how to install Python with Anaconda, the different tools that Anaconda provides, how to create a shortcut for jupyterl lab, and how to get started.
   - Pros: Simplifies the setup process and generally ensures compatibility among packages
   - Cons: Too much time and too much space needed and you will get a lot of tools that you will not use for this course
- Installing Python manually (*not at all recommended*):
   - Pros: Allows for more control over specific versions
   - Cons: Requires much additional effort in managing dependencies and configurations
- FGCU AppsAnywhere (*not recommended*):  
If you cannot install Python on your machine, [FGCU appsanywhere](https://www.fgcu.edu/its/appsanywhere/) has Anaconda.
     - Pros: You do not need to install anything and you can use Jupyterlab on the cloud
     - Cons: Many features such as adding Jupyterlab extensions will be disabled; can creat synce issues with OneDrive; Python version not often updated 

This tutorial shows you how to: 
- Install Miniconda that will install Python for you
- Use Miniconda to install JupyterLab
- Create a JupyterLab shortcut
- Install libraries needed for this course
- Get started with JuypterLab and Python

## Installing Python, JupyterLab, and required libraries with Miniconda

### 1. Install Python with Miniconda

You can easily install Python through Minoconda from [Minconda webpage](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html). You can find more information at [GeoPython - Installing Python](https://geo-Python-site.readthedocs.io/en/latest/course-info/installing-miniconda.html). 

After the installation is complete, from Windows Star Menu, open Anaconda Prompt(Miniconda3) and type:
```code
python --version
```
This will return to you the Python version that you have installed (e.g., Python 3.11.5). 

**Note:** Make sure you that you have a 64-bit system. If you do not know: Use the search icon near "Start Menu" and search for "About" that will take you to"Settings": "About" where you can know if you have a 32-bit or 64-bit processor. 

### 2. Install and run Jupyterlab 
You do not want to use Python in a black screen, so you need to install a graphical user interface(GUI). For programming languages, a GUI is called interactive development environment (IDE). The IDE that we will use for this course is [Jupyterlab](https://jupyter.org/), which is an open-source IDE for Python, Julia, R, MATLAB/Octave, and few other programming languages. 
  
In Python, we generally use `pip` or `conda` for installation. For details about JupyterLab installation, check the [JupyterLab documentation](https://jupyter.org/install), or follow these steps:

From the Windows Start menum, search for and open your Anaconda Prompt(Miniconda3), and install JupyterLab with pip by running this command:
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
Each time you use JupterLab, you do not want to open an Anaconda Prompt(Miniconda3) and type `jupyter lab`. You can create a shortcut to automatically lunch JupyterLab following these steps.

**Create Anaconda Prompt Shortcut:** 
   - Drag Anaconda Prompt(Miniconda3) from Start Menu to Desktop, which will create an Anaconda Prompt(Miniconda3) shortcut.
   - You can check that by clicking on it and then typing `jupyter lab` which will lunch JupyterLab.

**Customize Anaconda Prompt Shortcut:** 
   - To customize the shortcut to lunch JupyterLab automatically, right click on your shortcut and select "Properties".
   - Then at the end of the "Target" cell type
      ```code
      & jupyter lab && exit
      ```
      At my machine the content of the "Target" cell now looks something like this:
      ```
      %windir%\System32\cmd.exe "/K" C:\Users\username\AppData\Local\miniconda3\Scripts\activate.bat C:\Users\username\AppData\Local\miniconda3 & jupyter lab && exit
      ```
If this is unclear, check this [YouTube video](https://www.youtube.com/live/lD11l2vViqo?si=0PXs2GJLi_LqiuOC&t=465)
  
### 4. Change JupyterLab shortcut icon (*optional*)
In case you want your icon to look nice
- Download this [jupterlab icon](https://github.com/aselshall/git-tutorial-/blob/master/JupyterLab-icon.ico) and save it anywhere you like.
- If you do not like this icon, get any other icon that you like that has the extension `.ico`.
- Right click on the shortcut: "Change Icon": "Browse": Select the icon from where you saved it.
- You can now drag your icon from Desktop to Taskbar to make your JupyterLab handy.

### 5. Install basic libraries
From the miniconda terminal install these libraries one by one. You can install them now or before each lesson.   
    
#### Basic libraries: Pandas, NumPy and matplotlib :
```python
pip install pyarrow pandas matplotlib numpy lckr_jupyterlab_variableinspector
```

#### Gridded data libraries: Xarray and CartoPy   
```python
pip install xarray netCDF4 cartopy
```

#### Statistical analysis and machine learning libraries:
```python
pip install scipy seaborn statsmodels scikit-learn shap tensorflow
```

#### Google Earth engine (GEE) libraries:
```python
pip install earthengine-api geemap ipywidgets

```

#### Automated data download 
```python
pip install copernicusmarine dataretrieval requests
```
***Note:*** `dataretrieval` retrieves the major data types of USGS hydrology data that are available on the Web, as well as data from the Water Quality Portal (WQP), which currently houses water quality data from the EPA, USDA and USGS. Direct USGS data is obtained from a service called the National Water Information System (NWIS).

### 6. Install Jupyter AI (optional, highly recommended):
[Jupyter AI](https://github.com/jupyterlab/jupyter-ai) facilitates AI coding assistance by bring language models such as ChatGPT to your Jupyter environment. You first need to have an API key for your language model to work. For example, if you want to use ChatGPT, check this [file for OpenAI API key](https://aselshall.github.io/eds/L/L5/openai_api_key). Also, the installation time can be long, so you need to be patient.
    
To install Jupyter-AI with dependencies for all supported language models (not recommended):
```python
pip install jupyter-ai[all]
```
To install  Jupyter-AI wit with dependencies of selected model providers such as OpenAI, e.g., ChatGPT and Google, e.g., Gemini (recommended):
```python	
pip install jupyter-ai langchain-openai langchain-google-genai
```
The above comand provides two examples, but you can check the [model provider table](https://jupyter-ai.readthedocs.io/en/latest/users/index.html#model-providers) for information on supported providers and their dependencies. 

***Note***: Jupyter AI may not work for the current python or JupyterLab version. You might need to upgrade/downgrade your python version to meet the version requirement. Installing Jupyter AI can be time consuming and tricky, so you can skip it and use language models (e.g. ChatGPT) outside the Jupyter environment. If you want to give it a try, before you start you need to check [jupyter-ai](https://github.com/jupyterlab/jupyter-ai) documentation for requirements and instructions.

### 7. Additional Information (optional)

#### GeoPandas for shapefiles (optional):
```python
pip install geopandas contextily shapely adjustText
```
#### Specialized packages and plots (optional):
```python
pip install windrose
```

***Note***: This will not replace a GIS software such as ArcGIS Pro or QMap, but it is useful for integrating GIS maps in your workflow.  

#### Useful tips
Sometime you need to update your Python version, which you can do by creating a new environment. Here is how to upgrade from Python 3.11 to 3.12:
```python
conda create -n py312 python=3.12
```
Activate the new environment to take priority when you start Python
```python
conda activate py312
```
You can check your environments:
```python
conda info --envs
```
Then you can install everything at once, but creating a `requirements.txt` file with the following content:
```python
jupyterlab
pyarrow
pandas
matplotlib
numpy
lckr_jupyterlab_variableinspector
xarray
netCDF4
cartopy
scipy
seaborn
statsmodels
scikit-learn
shap
tensorflow
earthengine-api
geemap
copernicusmarine
dataretrieval
requests
jupyter-ai
langchain-openai
langchain-google-genai
geopandas
contextily
shapely
adjustText
windrose
```
Then install everything using:
```python
pip install -r requirements.txt
```


## Next steps
Now you have JupyterLab and Python installed , you can start with these: 
- Jupyter tutorial (*recommended*): [Getting Started with Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html) 
- Zero-to-hero Python tutorial (*highly recommended*): [Getting Started with Python](https://foundations.projectpythia.org/foundations/getting-started-python.html)

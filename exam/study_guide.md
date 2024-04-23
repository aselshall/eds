# Study Guide for Final Exam

**Exam Date:** Tuesday, April 30  
**Exam Time:** 03:00pm - 04:00pm  
**Location:** Holmes Engineering 439  

As we approach the final exam, I encourage you to diligently prepare for the exam. Here are some important details regarding the exam:

- The one hour final exam consists of 60 multiple-choice questions and select correct answer questions.
- The the exam is open book, but not open internet.
- Any form of academic dishonesty will result in a grade of zero for this exam.
- The questions will cover key topics from the 10 modules in the course, focusing mainly on basic materials.
- You can concentrate on the lessons, as the exam will not include exercise and homework questions.
- Expect a mix of easy and moderate questions to assess different levels of understanding.
- The exam will evaluate your grasp of general information discussed in class and your level of class participation.
- If you are regularly present in the class and consistant with practicing with homework and project, the exam should be easy.
  
To help you to prepare, the study guide includes key topics based on the exam questions, along with a few sample questions.

## 1. Introduction and General (~ 10 %)
- Lesson 1: Introduction to Environmental Data Science with Python
  - Common tasks in environmental data science
  - Programming languages used in environmental data science

- Lesson 2: Getting Started with JupyterLab and Python
  - Installing Python packages using pip
  - Programming languages supported by Jupyter
  - Benefits of using Jupyter Notebooks
  - Jupyter Notebook vs. JupyterLab

**Sample Questions:**     
     
**Question 1.** What are some common tasks in environmental data science?   
a) Analyzing satellite images of forests    
b) Predicting air quality based on weather data     
c) Processing data of Earth system models   
d) All of the above    
   
**Question 2.** Which of the following commands can be used to install Python packages using pip?   
a) pip install package_name   
b) py install package_name   
c) python install package_name    
d) pkg install package_name     
   
## 2. Python Basics  (~ 25%)
- Lesson 3: Python Basics 1 - Variables and Functions
  - Importing modules and libraries
  - Defining variables
  - Valid and invalid variable names

- Lesson 4: Python Basics 2 - Lists
  - Purpose of using lists
  - List indexing
  - Accessing and modifying list elements
  - List operations and methods

- Lesson 5: Python Basics 3 - Formatting
  - Formatting text and numbers using f-strings
  - Displaying numbers with decimal, scientific notation, and percentage

**Sample Questions:**   
    
**Question 3.** Which of the following is a valid variable name in Python?  
   a) `my_var1`  
   b) `1var`   
   c) `var_$`   
   d) None of the above  
      
**Question 4.** What happens when you try to access a variable that has not been defined?  
  a) Python automatically assigns a value to it  
  b) Python raises an error   
  c) Python prompts the user to define the variable  
  d) None of the above  
  
**Question 5.** What is the output of the following code?   
   ```python
   x = 5
   y = 3
   print(x + y)
   ```
   a) 5  
   b) 3  
   c) 8  
   d) Python raises an error   

**Question 6.** Which of the following is the correct way to call the `sqrt` function from the `math` module?  
  a) `math.sqrt()`    
  b) `sqrt(math)`    
  c) `math(sqrt)`   
  d) `sqrt()`   
   
**Question 7.** What is the output of the following code?
```python
my_list = [1, 2, 3, 4, 5]
print(my_list[-2])
```
a) 1   
b) 2   
c) 3   
d) 4    
     
**Question 8.** What will be the output of the following code ?
```python
percentage = 0.75
print(f"The percentage is {percentage:.1%}")
```
a) The percentage is 0.8  
b) The percentage is 75.0%  
c) The percentage is 75%  
d) The percentage is 0.8%  
    
## 3. Python Programming (~ 25%)
- Lesson 6: Python Programming 1 - Loops
  - for and while loops
  - Iterating over lists

- Lesson 7: Python Programming 2 - Conditional Statements
  - Purpose of else statement
  - Evaluating boolean conditions
  - Combining conditional statements

- Lesson 8: Functions

- Lesson 9: Scripts and Modules

**Sample Questions:**   

**Question 10.** Which loop in Python is better suited when the number of iterations is known?  
a) for loop  
b) while loop   
c) They are equally suited   
d) None of the above   
   
**Question 11.** What will be the output of the following code?   

   ```python
   numbers = [1, 2, 3, 4, 5]
   for num in numbers:
       print(num * 2)
   ```
   a) 2 4 6 8 10   
   b) 1 2 3 4 5   
   c) 1 2 3 4 5 2 4 6 8 10   
   d) SyntaxError: invalid syntax   

**Question 12.** What does the following while loop do?
```python
count = 0
while count < 5:
    print("The count is:", count)
    count += 1
```
a) It prints the count from 1 to 5  
b) It prints the count from 0 to 4  
c) It prints "The count is:" infinitely  
d) Python raises an error  
   
**Question 13.** What will be the output of this code?   
```python
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is less than or equal to 5")
```
a) x is greater than 5   
b) x is less than or equal to 5   
c) x is 10   
d) SyntaxError: invalid syntax   
    
**Question 14.** What will be the output of the following code?   
```python
x = 15
if x > 5 and x < 15:
    print("Between 5 and 15")
else:
    print("Outside the range")
```
a) Outside the range  
b) Between 5 and 15  
c) Error   
d) None of the above   
   
**Question 15.** Consider the following code:  
```python
def process_data(data):
   result = data**2
   return result

output = process_data(5)
print(result)
```
What will be printed?  
a) 5  
b) 10  
c) 25  
d) None of the above   
  
**Question 16.** Consider the following code saved in a script file named 'my_script.py':    
```python
def greet(name):
    print(f"Hello, {name}!")

def multiply(x, y):
    return x * y
```
How can you import and use the greet function from this script in another Python file?   
a) `import my_script.greet`   
b) `from my_script import greet`   
c) `from my_script import greet()`   
d) `import my_script`   
    
## 4. Pandas  (~ 15%)
- Lessons 10-14: Pandas Primer
  - Installing and importing Pandas
  - Reading CSV files
  - Exploring Pandas DataFrames
  - Filtering and querying data

**Sample Questions:**

**Question 18.**  Select the most accurate answer  
a) You can install pandas using pip install pandas  
b) You can install pandas using pip install pandas or pip download pandas  
c) pandas can be only installed with pip if you have conda or miniconda   
d) none of the above  
     
**Question 19.** What is the output of the following code?    
   ```python
   import pandas as pd
   data = pd.read_csv("data.csv")
   print(data.shape)
   ```
   a) The number of rows and columns in the DataFrame   
   b) The number of unique values in each column of the DataFrame   
   c) No output or error as `.shape` is not a method   
   d) None of the above  
   
**Question 20.** Select all line codes that can display the first three rows of this `df` DataFrame:  
|    |   A |   B |
|---:|----:|----:|
|  0 |  10 |   1 |
|  1 |  20 |   2 |
|  2 |  30 |   3 |
|  3 |  40 |   4 |
|  4 |  50 |   5 |
|  5 |  60 |   6 |
  
1) `display(df.iloc[0:3])`  
2) `display(df.iloc[0:3,:])`     
3) `display(df.iloc[:,0:3])`    
4) `display(df.loc[0:3])`   
5) `display(df.loc[0:3,:])`    
6) `display(df.loc[0:2])`   
7) `display(df.loc[0:2,:])`    
8) `df.head(3)`    
9) `df.head()`   
10) `display(df[0:3, :])`    
11) `display(df[0:3])`   
12) `display(df[0:2])`    


**Question 21.** Suppose you have a DataFrame named df with columns 'A', 'B', and 'C'. What does the following code do?   
```python
df = df.groupby('A').sum()
```
a) Groups the DataFrame by unique values in column 'A' and sums the values in column 'A' for each group   
b) Groups the DataFrame by unique values in column 'A', sums the values in columns 'B' and 'C' for each group  
c) Returns a syntax error  
d) None of the above  
    
## 5. AI Coding Assistance (< 5%)
- Lesson 15: AI Coding Assistance
  - Pros and cons of generative AI in Python learning and productivity
  - Integrating AI code assistants in Jupyter Notebook

**Sample Questions:**   
**Question 22.**
What is the potential downside of relying too much on generative AI for coding tasks?   
a) It may lead to decreased efficiency and productivity due to slower response times  
b) It may result in code plagiarism, lack of originality and dependency on AI for coding tasks   
c) It may increase the likelihood of code errors and bugs   
d) It may require extensive computational resources   
     
## 6. Data Science Workflow (< 5%)
- Lessons 16-17: Data Science Workflow
  - Steps in the data science workflow
  - Data preprocessing techniques

**Sample Questions:**   
**Question 23** What is the first step in the data science workflow?   
a) Data analysis  
b) Data visualization    
c) Data collection   
d) Data preprocessing  
  
## 7. NumPy (~ 5%)
- Lessons 18-20: NumPy Basics
  - Creating NumPy arrays
  - Indexing and slicing arrays
  - Performing mathematical operations

**Sample Questions:**   
**Question 24** What is the primary data structure used in NumPy?   
a) Lists   
b) Tuples   
c) Arrays   
d) Sets  


**Question 25** Consider the following code:   
```python
import numpy as np

arr = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])

result = arr[:, 1]
print(result)
```
This code   
a) selects all rows of the first column of the array   
b) selects all rows of the second column of the array   
c) selects the second row of all columns of the array  
d) none of the above  
   
## 8. Matplotlib (~ 5%)
- Lessons 21-23: Matplotlib Basics
  - Purpose and features of Matplotlib
  - Working with Figure and Axes objects
  - Creating line plots and scatter plots
  - Customizing plots

**Sample Questions:**
**Question 26.** Which of the following statements accurately describes Matplotlib?   
a) Matplotlib is the best choice for specialized statistical plots among plotting libraries in Python   
b) Matplotlib is the best choice for interactive plots among plotting libraries in Python   
c) Matplotlib is a versatile plotting library for creating static, interactive, and animated visualizations   
d) Matplotlib is the best choice for for 3D visualization tasks among plotting libraries in Python   

**Question 27.** Consider the following code:  
```python
import matplotlib.pyplot as plt

fig, ax = plt.subplots()
ax.plot([1, 2, 3, 4], [1, 4, 9, 16])
ax.set_xlabel('X-axis')
ax.set_ylabel('Y-axis')
ax.set_title('Line Plot')
plt.show()
```
Through `.plt.subplots()` function you can  
a) create a new figure and axes object  
b) add a title  
c) adjust figure size  
d) do all of the above  

**Question 28.** Consider the following code:   
```python
import matplotlib.pyplot as plt
fig, ax = plt.subplots()
ax.plot([1, 2, 3, 4], [1, 4, 9, 16], linestyle='--')
plt.show()
```
What does linestyle='--' do in this code?  
a) Sets the line style to dashed line   
b) Sets the line style to dotted line   
c) Sets the line style to solid line  
d) None of the above  
   
## 9. Xarray and CartoPy (~ 10%)
- Lessons 24 Climate Data - CMIP6 and Remote Sensing   
  - General information about CMIP6 and remote sensing data
    
- Lessons 25-26: Xarray Basics
  - Working with NetCDF data
  - Analyzing and visualizing climate data
  - Performing operations on Xarray DataArrays and Datasets

- Lesson 27: CartoPy Basics
  - Map projections and GeoAxes
  - Creating regional maps with raster and vector data
  - Customizing map extent and features

**Sample Questions:**   
**Question 29.** Which of the following best describes CMIP6?   
a) A satellite launched by NASA for remote sensing of climate data    
b) A dataset containing historical climate observations from the past century    
c) A modeling project providing climate model output      
d) A project providing weather forecasting models   
   
**Question 30.** What is the primary purpose of Xarray in Python?  
a) Xarray is a library for statstical analysis   
b) Xarray is the best tool for working with tabular data   
c) Xarray is a library for working with labeled arrays and datasets in Python   
d) Xarray is a package for web development and data storage  

**Question 31.** Consider the following code:
```python
import matplotlib.pyplot as plt

#Xarray DataSet ds
ds['temperature'].plot()   #temperature shape (50, 50)
plt.show()
```
What does ds['temperature'].plot() do in this code?   
a) Plots the temperature data from the dataset using Matplotlib as a line plot  
b) Plots the temperature data from the dataset using Matplotlib as a pcolormesh plot  
c) Returns an error as xarray has no built-in plotting method   
d) None of the above  

**Question 32.** Consider the following code:  
```python
import xarray as xr
import pandas as pd
import numpy as np
dates = pd.date_range('2024-01-01', periods=240, freq='M')  
latitudes= [24.5, 26.5, 28.5, 30.5]
size=(len(dates), len(latitudes))
zos = np.round(np.random.uniform(-1, 1, size= size), 2) #sea surface height [m]
ds = xr.Dataset({'zos': (('date', 'lat',), zos)}, coords={'date': dates, 'lat': latitudes})
ds.zos.mean(dim=('lat')).plot()
```
What will this code plot?   
a) time series plot showing mean zos varying with time with monthly intervals  
b) time series plot showing mean zos varying with lat with monthly intervals  
c) lat contour plot showing mean zos varying with time with monthly intervals  
d) nothing because, unlike pandas, xarray does not have built-in plotting  

**Question 33.** What is the purpose of specifying subplot_kw={'projection': ...} when creating subplots in CartoPy?  
a) To define the color scheme for the subplots   
b) To specify the resolution of the subplots  
c) To set the extent of the subplots  
d) To define the map projection for the subplots   
   
**Question 34.** What does the term "map projection" refer to in the context of CartoPy?  
a) The process of creating a map by projecting points on Earth's surface onto a flat surface  
b) The method of coloring different regions on a map  
c) The process of adding geographic features such as coastlines and rivers to a map  
d) The technique of overlaying multiple plots on a single map figure  
   
## 10. Google Earth Engine and GeeMap
- Lesson 27: Google Earth Enginer and GeeMap
  - General information about Google Earth Enginer and GeeMap

**Sample Questions:**  
**Question 35.**
What is the primary purpose of Google Earth Engine (GEE) in environmental data science?  
a) To provide satellite imagery for visual inspection  
b) To analyze and process large-scale geospatial datasets  
c) To create custom maps for web applications  
d) To collect ground-level environmental data  
  
Best of luck!

## Keys:

**Question 1.** d) All of the above    
**Question 2.** a) pip install package_name   
**Question 3.** a) `my_var1`  
**Question 4.** b) Python raises an error   
**Question 5.** c) 8  
**Question 6.** a) `math.sqrt()`    
**Question 7.** d) 4    
**Question 8.** b) The percentage is 75.0%  
**Question 10.** a) for loop  
**Question 11.** a) 2 4 6 8 10   
**Question 12.** b) It prints the count from 0 to 4  
**Question 13.** a) x is greater than 5   
**Question 14.** a) Outside the range   
**Question 15.** c) 25  
**Question 16.** b) `from my_script import greet`   
**Question 18.**  a) You can install pandas using pip install pandas  
**Question 19.** a) The number of rows and columns in the DataFrame   
**Question 20.**  Correct answers       
- `display(df.iloc[0:3])`  
- `display(df.iloc[0:3,:])`  
- `display(df.loc[0:2])`  
- `display(df.loc[0:2,:])`  
- `df.head(3)`  
- `display(df[0:3])`

**Question 21.** b) Groups the DataFrame by unique values in column 'A', sums the values in columns 'B' and 'C' for each group  
**Question 22.** b) It may result in code plagiarism, lack of originality and dependency on AI for coding tasks 
**Question 23** c) Data collection   
**Question 24** c) Arrays   
**Question 25** b) selects all rows of the second column of the array   
**Question 26.** c) Matplotlib is a versatile plotting library for creating static, interactive, and animated visualizations   
**Question 27.** a) create a new figure and axes object  
**Question 28.** a) Sets the line style to dashed line   
**Question 29.** c) A modeling project providing climate model output      
**Question 30.** c) Xarray is a library for working with labeled arrays and datasets in Python   
**Question 31.** b) Plots the temperature data from the dataset using Matplotlib as a pcolormesh plot  
**Question 32.**  a) time series plot showing mean zos varying with time with monthly intervals  
**Question 33.** d) To define the map projection for the subplots   
**Question 34.** a) The process of creating a map by projecting points on Earth's surface onto a flat surface  
**Question 35.** b) To analyze and process large-scale geospatial datasets  

Best of luck!



# Study Guide for Final Exam

**Exam Date:** Tuesday, April 30  
**Exam Time:** 03:00pm - 04:00pm  
**Location:** Holmes Engineering 439  

As we approach the final exam, I encourage you to diligently prepare for the exam. Here are some important details regarding the exam:

- The one hour final exam consists of 60 multiple-choice /select all correct questions.
- The the exam is open book, but not open internet.
- Any form of academic dishonesty will result in a grade of zero for this exam.
- The questions will cover key topics from the 10 modules in the course, focusing mainly on basic materials.
- You can concentrate on the lessons, as the exam will not include exercise and homework questions.
- Expect a mix of easy and moderate questions to assess different levels of understanding.
- The exam will evaluate your grasp of general information discussed in class and your level of class participation.
- If you are regularly present in the class and consistant with practicing with homework and project, the exam should be easy.
  
To help you to prepare, the study guide includes key topics based on the exam questions, along with a few sample questions.

## 1. Introduction
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
   
## 2. Python Basics  
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
    
## 3. Python Programming
- Lesson 6: Python Programming 1 - Loops
  - for and while loops
  - Iterating over lists

- Lesson 7: Python Programming 2 - Conditional Statements
  - Purpose of else statement
  - Evaluating boolean conditions
  - Combining conditional statements

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
   

## 4. Pandas
- Lessons 10-14: Pandas Primer
  - Installing and importing Pandas
  - Reading CSV files
  - Exploring Pandas DataFrames
  - Filtering and querying data

**Sample Questions:**
What is the output of the following code?
   ```python
   import pandas as pd
   data = pd.read_csv("data.csv")
   print(data.shape)
   ```
   a) The number of rows and columns in the DataFrame
   b) The number of unique values in each column of the DataFrame
   c) No output or error as `.shape` is not a method
   d) None of the above
   
## 5. AI Coding Assistance
- Lesson 15: AI Coding Assistance
  - Pros and cons of generative AI in Python learning and productivity
  - Integrating AI code assistants in Jupyter Notebook

**Sample Questions:**   

## 6. Data Science Workflow
- Lessons 16-17: Data Science Workflow
  - Steps in the data science workflow
  - Data preprocessing techniques

**Sample Questions:**   

## 7. NumPy
- Lessons 18-20: NumPy Basics
  - Creating NumPy arrays
  - Indexing and slicing arrays
  - Performing mathematical operations

**Sample Questions:**   

## 8. Matplotlib
- Lessons 21-23: Matplotlib Basics
  - Purpose and features of Matplotlib
  - Working with Figure and Axes objects
  - Creating line plots and scatter plots
  - Customizing plots

**Sample Questions:**

## 9. Xarray and CartoPy
- Lessons 24-26: Xarray Basics
  - Working with NetCDF data
  - Analyzing and visualizing climate data
  - Performing operations on Xarray DataArrays and Datasets

- Lesson 27: CartoPy Basics
  - Map projections and GeoAxes
  - Creating regional maps with raster and vector data
  - Customizing map extent and features

**Sample Questions:**   

## 10. Google Earth Engine and GeeMap
- Lesson 27: Google Earth Enginer and GeeMap
  - General information about Google Earth Enginer and GeeMap

**Sample Questions:**  
  

Best of luck!

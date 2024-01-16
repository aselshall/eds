<h1 style="color:green; text-align:center;"> Homework 1 Python Basics </h1>  

**Instructions:**
* LLM Not Permitted (Check syllabus for details)
* Answer all questions in one notebook
* Rename notebook file name to `HW1_YourLastName_YourFirstName`
* Submit your notebook to Canvas by the due date on Canvas
  
## Problem 1 - Happiness rating

**The objective** of this problem is to demonstrate that you can use Jupyter Notebook to write an run a simple python code.

This problem is modified from [Geo-python - Exercise 1](https://github.com/Geo-Python-2023/Exercise-1). You will assess your happiness based on two of life's most important happiness factors: Ice cream and sleep!

1. Create a new notebook and rename it to `HW1_LastName_FirstName`.
2. Create markdown cell with heading "Problem 1 Happiness Rating" and run the cell
3. Create code cell to define some variables and do some calculations as follows:
4. Define variable `my_name` to store your name
5. Define variabless `ice_cream_rating`, and `sleeping_rating` to store an integer value (whole number) between 0 and 10 that reflects your general opinion about how much you enjoy eating ice cream and enjoy sleeping, respectively
6. Calculate the average of your `ice_cream_rating` and `sleeping_rating` variables using a variable called `happiness_rating`
7. Use print function with the variables that you defined to print the something like this (with your inputs)
```
My name is Wormfy Noseborn and my happiness rating is 8.5 out of 10, or 85.0%
```
8. Run your code cell and show output to screen.

## Problem 2 - Becoming a millionare

**The objectives** of this problems are to show that you can perform math operations in python and use math functions (e.g., `log`) that you did not learn in class.

According to [New Trader U: 3 Low-Effort Ways To Become A Millionaire](https://www.newtraderu.com/2023/05/07/3-low-effort-ways-to-become-a-millionaire/), Standard and Poor's 500 index fund (S&P 500) tracks the stock performance of 500 of the largest companies listed on stock exchanges in the US. The average historical rate an investor can expect long-term on S&P 500 is 8% annual compounded growth. The formula is:   
$$FV = PM * \frac{[(1 + r)^{nt} – 1]}{r}$$    
Where:      
FV:  Future value of the investment (e.g., \$1,000,000)     
PM: Monthly investment amount (e.g., \$300)     
r:   Monthly interest rate       
n:   Number of times the interest is compounded per year (i.e., 12 for monthly compounding)     
t:   Number of years (e.g., 20 years)   

To convert annual interest rate of 8% to monthly interest rate you can use this formula   
$$r = (1 + 0.08)^{1/n} – 1$$

For example,  for FV= \$1,000,000 and t = 40 years, then PM ≈ \$310.5. Note while there is wide variance in monthly and annual returns, long-term destination will likely lead to being a millionaire based on historical performance of past 100 years. 

**Answer these two questions:**       
**(1)** Write a code to check how much do you need to invest monthly to become a millionaire in 25 years? Display your answer as "For a future value of \$ 1.0 million in 25 years, you need to invist \\$ 1100.0 per month". Note that \$ 1100.0 is rounded and the actual value is 1100.120953605599.   
  
**(2)** Write a code to find out that if you will invest \\$1000 per month, after how many years will you become a millionaire? Display your answer as "If you invisited \\$1000.0 per month, you will become a milloire in 25.5 years". **Note** you need to import [math](https://docs.python.org/3/library/math.html) module to solve the exponential equation using logarithms. We did not learn logarithms, but we learned how to find functions in the documentation of the math module.   

## Problem 3 - List 
**The objectives** of this problem is that you demonstrate that you have a good understanding python list including different methods of list, and that you can find help in python beyond what you learned in the class (e.g., to find and apply new methods that you did not learn in class).

You are given a list representing daily average temperatures (in degrees Celsius) for a week in Estero, FL as follows.
```python
temperatures = [16, 17, 18, 15, 17, 19, 20]
``` 
**Answer these questions:**   
1. Find the number of days in the dataset.   
2. A new average temperature of 21 degrees Celsius was recorded for the next day (Monday of the following week). Add the new temperature reading.   
3. Add to the list this other list of temperatures from a different region: [25, 26, 25, 27, 28, 26, 27]. You did not learn the method to add a list to another list. Check [Finding Help in Python](https://github.com/aselshall/eds/blob/main/L/L1/find_help_python.md) to get ideas on how to find help.   
4. Use python functions to find the highest and lowest temperatures in the list.   
5. Replace the third from the last temperature in the list (i.e., 28) with 35.   
6. Create a list of temperatures converted to Fahrenheit. The formula for converting Celsius to Fahrenheit is (Celsius * 9/5) + 32 (Bonus questions).

Print you answers clearly (e.g., Number of days: 7).

## Problem 4 - Using f-formatting

**The objectives** of this problem is to show that you can use f-formatting with scientific notation and percentage.

Consider the concentration of particulate matter (PM2.5) in the air as follows.
```python
#pm2.5 concentration in micrograms per cubic meter (µg/m³)
pm25_concentration=0.215  
# reference standard or permissible limit in micrograms per cubic meter (µg/m³)
pm25_limit=10
```
**Write a python code to perform the following:**   
(1) Calculate this ratio:   
$$\text{PM2.5 Ratio} = \frac{\text{PM2.5 Concentration}}{\text{PM2.5 Permissible Limit}}$$   

(2) Print this ratio using f-formatting as follows:  
  
"A PM2.5 concentration of 2.15E-1 µg/m³ is approximately 2.15% of the permissible limit."
  
**Note**  The concentration format has 2 decimal places in scientific notation, and the ratio format is in percentage with 2 decimal places. 

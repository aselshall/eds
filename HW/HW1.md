<h1 style="color:green; text-align:center;"> Homework 1 Python Basics </h1>  

**Instructions:**
* LLM Not Permitted  
* Answer all questions in one notebook
* Rename notebook file name to `YourLastName_YourFirstName`
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
$$
FV = PM * \frac{[(1 + r)^{nt} – 1]}{r} 
$$
Where:      
FV:  Future value of the investment (e.g., \\$1,000,000)     
PM: Monthly investment amount (e.g., \\$300)     
r:   Monthly interest rate       
n:   Number of times the interest is compounded per year (i.e., 12 for monthly compounding)     
t:   Number of years (e.g., 20 years)   

To convert annual interest rate of 8% to monthly interest rate you can use this formula $ r = (1 + 0.08)^{1/n} – 1  $

For example,  for FV= \\$1,000,000 and t = 40 years, then PM ≈ \\$310.5. Note while there is wide variance in monthly and annual returns, long-term destination will likely lead to being a millionaire based on historical performance of past 100 years. 

**Answer these two questions:**       
**(1)** Write a code to check how much do you need to invest monthly to become a millionaire in 25 years? Display your answer as "For a future value of \\$ 1.0 million in 25 years, you need to invist \\$ 1100.0 per month". Note that \$ 1100.0 is rounded and the actual value is 1100.120953605599.   

# Lab exercises 
### 1st lab session (9 Jan 2019)

Please submit the following exercise:
1.1 List and Dictionaries

   Put your name and year of study in a **list**. Use the `print()` function to print `My name is ` followed by your name and a full stop `.`. On the next line, print `I am a year ` followed by your year of study, and ` student.`. 

   Sample output:
   ``` 
   My name is Joey. I am a year 1 student.
   ```
   Now put your name and year of study in a **dictionary**. Use the `print()` function to generate the same output.

1.2 Functions and Calculations

   Define a function for the following formula, which calculates the saturation vapor pressure of a temperature:

   ![Saturation vapour pressure](./images/sat_vapor_pressure.png)

   It is given that the air temperature is now 18 degree Celsius and the dew point temperature is 13.5 degree Celsius, find the relative humidity (in %). Use the `print()` function to print `The relative humidity is ` followed by your answer and the percentage sign `%` and a full stop `.`. 

   Sample output:
   ``` 
   The relative humidity is 30.1%.
   ```
   Optional: Learn to use `format()` to limit the output of your answer to one decimal place.

You may submit your answers in .ipynb or .py format on Blackboard. Make sure you name your file in a meaningful way and don't leave any space(s) in the file name. (I don't want to receive something like "Untitled.ipynb", or "a.py")

### 2nd lab session (14 Jan 2019)

You are not required to submit today's exercises.

2.1 Function and if statement

   Define a function to calculate the potential temperature from actual temperature (in degree Celsius, remember you need to convert it into Kelvin) and pressure (in hPa). Use if statements (if/elif/else) to reject any of the following scenarios:
   1. Input pressure is negative;
   2. Input pressure is larger than 10000hPa;
   3. Input actual temperature is smaller than -273.15 degree Celsius.
   
   Under the if statements, you can either print an error message, displaying the corresponding scenarios listed above, or use error handling tools in Python (e.g. raise ValueError('*error_message*) ). Learn more about error handling here: [Python Exceptions: An Introduction – Real Python](https://realpython.com/python-exceptions/)

2.2 While loop

   Construct a while loop to divide a number of your choice, e.g. 1.4, by 2 by many times until it becomes smaller than 0.00001.
   
   Note: this is part of the bisection method, which is a simple numerical method of solving an equation.
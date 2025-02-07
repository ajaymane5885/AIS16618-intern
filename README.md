# AIS16618-intern
#Day 1:

1.Variable Declaration Rule:
i) Variable name must be shart with letter or (__)underscore character 
ii) A variable name cannot start with number 
iii) Only contain alphanumeric characters and underscore ex.(A_z,a-z,0-9,:"-") 
iv) Variable name are case sensitive

2.Operators: 
i) Arithmatic operators(+,-,*,/,**,%)
ii) Assingment operators(+=,-=,*=,/=)
iii) Comparision operators(>,<,==,!=,<=,>=)
iv) Logical operators(and,or,not)

3.List: List creation,append,insert,pop,copy,sort,len,etc.

4.Tuple: append,insert,pop,copy,sort,count,reverse,index,extend,remove,etc.

5.Set: Set creation,add,remove,discard,pop,clear,union,update,intersection,intersection_update,difference,difference_update,symmetric_difference,symmetric_difference_update,etc.

6.Dictionarie: Dictionarie creation,get,keys,values,items,update,pop,popitem,clear,copy,etc.

7.Number: There are three numeric types in Python:int,float,complex.

8.String: Assign a string,len,upper,lower,strip,replace split,title,capitalize,casefold,encode,format,isalpha,isalnum,isascii,isdecimal,isdigit,islower,isupper,etc.

#Day 2:

1.If condition: if condition with 10 example,some example like-greater less,sign of number,even odd,empty,within range,key exists,none,etc.

2.If else condition: if else condition with 10 example,some example like- even odd,greater less,leap year,palindrome,perfect square,vowel,divisible by,etc.

3.If elif condition: if elif condition with 10 example,some example like- grade,quadrant,age groups,time period,sign of number,even odd,greater less,valid triangle,triangle types,discount rate,etc.

4.For loop: for loop with 10 example,some example like- iterating over a (list,range,string,tuple,dictionary),break statement,multiple lists,etc.

5.While loop: while loop with 10 example,some example like- count number,print Numbers (reverse,even,sum,squares),reverse a string,print Pattern,find factorial,doubling a number,print characters of a string,etc.

#Day 3:

1.Break statement: The break statement is used to exit a loop prematurely, regardless of whether the loop's condition has been satisfied or not. When Python encounters a break statement inside a loop (such as a for or while loop), it immediately exits the loop and continues with the next statement after the loop.The break statement provides a flexible way to control the flow of execution within loops, allowing you to exit them under specific conditions.

2.Pass statement: The pass statement is a null operation. It serves as a placeholder within a block of code where syntactically some code is required, but you don't want to perform any action. It essentially does nothing when executed and is often used as a placeholder for future code implementation or as a way to create empty code blocks that are required by Python's syntax.

3.Continue statement: The continue statement is used to skip the rest of the code inside a loop for the current iteration and proceed to the next iteration of the loop. When Python encounters a continue statement inside a loop (such as a for or while loop), it skips the remaining statements inside the loop's body for the current iteration and moves to the next iteration.

4.Statistical user define functions: Statistical user-defined functions in Python are custom functions that perform various statistical calculations on data. These functions are designed to analyze numerical data and provide useful statistical information such as mean, variance, standard deviation, median, mode, etc. 

A brief explanation of some statistical user-defined functions in Python:

Mean: Calculates the average value of a dataset by summing all the values and dividing by the total number of values.

Variance: Measures the spread or dispersion of data points around the mean. It calculates the average of the squared differences from the mean.

Standard Deviation: Represents the amount of variation or dispersion in a dataset. It is the square root of the variance and provides a measure of how spread out the values are.

Median: Determines the middle value of a dataset when it is sorted in ascending order. It is resistant to outliers and provides a robust measure of central tendency.

Mode: Identifies the value that appears most frequently in a dataset. It is useful for identifying the most common observation or value in a dataset.

Range: Represents the difference between the maximum and minimum values in a dataset. 

Sum: Calculates the total sum of all values in a dataset.

Count: Determines the number of elements or observations in a dataset.

Minimum: Identifies the smallest value in a dataset.

Maximum: Identifies the largest value in a dataset.

5.Logical user define functions: Logical user-defined functions evaluate conditions and return boolean values (True or False) based on the outcome of the logic. Logical user-defined functions are widely used in programming to implement conditional logic, decision-making, and filtering operations.

A brief explanation of some common logical user-defined functions in Python:

Even or Odd: A function that determines whether a given number is even or odd. It typically returns True if the number is even and False if it's odd.

Prime Number: A function that checks whether a given number is a prime number. It returns True if the number is prime and False otherwise.

Positive or Negative: A function that determines whether a given number is positive or negative. It returns True if the number is positive and False if it's negative.

Leap Year: A function that checks whether a given year is a leap year according to the leap year rules. It returns True if the year is a leap year and False otherwise.

Pass/Fail: A function that evaluates whether a student's score meets the passing criteria. It returns True if the score is above the passing threshold and False if it's below.

Grade Assignment: A function that assigns grades to student scores based on predefined grading criteria. It returns the grade (e.g., 'A', 'B', 'C', etc.) corresponding to the score.

Perfect Square: A function that determines whether a given number is a perfect square. It returns True if the number is a perfect square and False otherwise.

Century Year: A function that checks whether a given year is a century year (ending with '00'). It returns True if the year is a century year and False otherwise.

#Day 4:

#Numpy Library: NumPy provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays efficiently.

Key Features:

Arrays: NumPy arrays are a powerful data structure for holding and manipulating large arrays of numerical data. They are much more efficient than Python lists for numerical operations.

Mathematical Functions: NumPy provides a wide range of mathematical functions that operate element-wise on arrays, such as trigonometric functions, exponential and logarithmic functions, etc.

Broadcasting: NumPy's broadcasting allows arithmetic operations to be performed on arrays of different shapes, which can greatly simplify code.

Linear Algebra: NumPy provides functions for linear algebra operations, such as matrix multiplication, inversion, eigenvalues, etc.

Random Number Generation: NumPy includes functions for generating random numbers with various distributions.

#Notebooks:

1.Numpy Basic: Intro, Getting Started, Creating Arrays, Array Indexing, Array Slicing, Data Types, Copy vs View, Array Shape, Array Reshape, Array Iterating, Array Join, Array Split, Array Search, Array Sort, Array Filter.

2.NumPy Random: Intro, Data Distribution, Random Permutation, Seaborn Module, Normal Distribution, Binomial Distribution, Poisson Distribution, Uniform Distribution, Logistic Distribution, Multinomial Distribution, Exponential Distribution, Chi Square Distribution, Rayleigh Distribution, Pareto Distribution, Zipf Distribution.

3.NumPy ufunc: Intro, Create Function, Simple Arithmetic, Rounding Decimals, Logs, Summations, Products, Differences, Finding LCM, Finding GCD, Trigonometric, Hyperbolic, Set Operations.

#Day 5:

#Pandas Library: Pandas is a Python library used for working with data sets. It has functions for analyzing, cleaning, exploring, and manipulating data.

1.Series: We create a Series from a list and dictionary, We create a Series with a custom index and scalar value. These are some basic ways of creating a Series in Pandas. Once you have created a Series, you can perform various operations like Indexing and Slicing, Arithmetic Operations, Element-wise Operations, Boolean Operations,etc.

2.DataFrame: To create a simple Pandas DataFrame. #For CSV files, you can use pd.read_csv('file.csv'). CSV (Comma Separated Values) files are plain text files where each line represents a row of data, and values within each row are separated by commas or other delimiters. #For Excel files, you can use pd.read_excel('file.xlsx'). Excel files are binary files that can contain multiple sheets, each with rows and columns of data. Both functions automatically infer the data format, but you can specify additional parameters to customize the import process, such as specifying column names, skipping rows, or selecting specific sheets in Excel files. #Dataframe create using matrix,such as from lists,from numpy array,with Custom Column Names,with custom index,with Mixed Data Types. #To create dataframe using dictionary such as from Dictionary of Lists,from Dictionary of NumPy Arrays,with Custom Index,with Selected Columns,from Nested Dictionary.

3.DataFrame Operation: value_counts() Counting the occurrences of unique values in a column, apply() Applying a function along the axis of the DataFrame, unique() Getting unique values in a column, nunique() Counting the number of unique values in a column, describe() Generating descriptive statistics of the DataFrame, Finding the Index of Maximum Values with idxmax().

4.Selection: #DataFrame col,row selection using loc and iloc. #Conditional Selection with Boolean Indexing and query(). #Adding, Deleting, and Updating Columns. #Setting Index and Removing Index. #Operation(+,-,*,|)between two columns.

5.Missing Value: #Missing value checking using isnull() and isna(). #Missing value dropping by row and by col. #Missing value fill(mean,median).

#Day 6:

1.Matplotlib Library: Matplotlib is a low level graph plotting library in python that serves as a visualization utility.

#Import Matplotlib, Plotting, Markers, Linestyle, Labels and Title, Adding Grid Lines, Subplots, Scatter, Bars, Histogram, Pie Charts.

2.Seaborn Library: Seaborn is a library that uses Matplotlib underneath to plot graphs. It will be used to visualize random distributions.

#Import Seaborn, Plotting a Distplot, Releational plots(Scatter Plot, Line Plot, Joint plot), Categorical plots(Bar Plot, Box Plot, Count Plot), Distribution Plots(Histogram, KDE Plot, Rug Plot), Regression plots(Linear regression plot, Residual Plot), Matrix Plots(Correlation matrix(Heatmap), Clustermap), Multi-plot Grids(FaceGrid, PairGrid, JointGrid, Violin plot).
 
#Day 7:

1. Numpy Exercise

2. Ecommerce Purchases Exercise

3. SF Salaries Exercise

#Day 8: Case Study: 1

#Download titanic data
1) read data and import necessary libraries 
data preprocessing : 
2) find missing value ,fill or drop
3) if need drop variable 
4) label encoding for categorical variable 

#Visualisation:
EDA: bar plot , scatter plot ,joint bar plot,Pai chart, etc

#Model building:
5)choose dependent and independent variables
6) split data into train test ,80:20
7)import naive bay’s algorithms 
8) fit naive bays model on train data
9)predict text data using fitted model

Model evaluation: 
10) find accuracy 
11)find classification report 
12)find confusion matrics 

#Same process for :
8) knn algorithm 
8)decision tree

#Comparison:
Naive bays , knn,decision tree compair 
Accuracy,recall, precision











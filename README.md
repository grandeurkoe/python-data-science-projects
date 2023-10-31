# Python Data Science Projects

These python data science projects are built in correspondence with " [100 Days of Code - The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) " course. This course was taught by London's App Brewery top instructor Angela Yang.<br/>

Each project has been built from scratch with minimal to no assistance.<br/>

### Day 072 - College Major vs Your Salary Analysis

This project involves analyzing the post-university salaries of graduates by major. 

**Learning Points & Summary**

- Use `.head()`, `.tail()`, `.shape` and `.columns` to explore your DataFrame and find out the number of rows and columns as well as the column names.
- Look for NaN (not a number) values with `.findna()` and consider using `.dropna()` to clean up your DataFrame.
- You can access entire columns of a DataFrame using the square bracket notation: `df['column name']` or` df[['column name 1', 'column name 2', 'column name 3']]`
- You can access individual cells in a DataFrame by chaining square brackets `df['column name'][index]` or using `df['column name'].loc[index]`
- The largest and smallest values, as well as their positions, can be found with methods like `.max()`, `.min()`, `.idxmax()` and `.idxmin()`.
- You can sort the DataFrame with `.sort_values()` and add new columns with` .insert()`.
- To create an Excel Style Pivot Table by grouping entries that belong to a particular category use the `.groupby()` method

![College Major vs Your Salary Analysis](college-major-vs-your-salary/data-exploration-pandas-college-major.gif)

### Day 073 - Programming Languages

This project involves analyzing the popularity of different programming languages over time. Additionally, create beautiful charts using Matplotlib.

**Learning Points & Summary**

- use `.groupby()` to explore the number of posts and entries per programming language
- convert strings to Datetime objects with `to_datetime()` for easier plotting
- reshape DataFrame by converting categories to columns using `.pivot()`
- use `.count()` and `isna().values.any()` to look for NaN values in our DataFrame, which we then replaced using `.fillna()`
- creat (multiple) line charts using `.plot()` with a for-loop
- style charts by changing the size, the labels, and the upper and lower bounds of our axis.
- add a legend to tell apart which line is which by color.
- smooth out our time-series observations with `.rolling().mean()` and plot them to better identify trends over time.

![Programming Languages](programming-language/programming-languages.gif)

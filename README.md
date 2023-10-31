# Python Data Science Projects

These python data science projects are built in correspondence with " [100 Days of Code - The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) " course. This course was taught by London's App Brewery top instructor Angela Yang.<br/>

Each project has been built from scratch with minimal to no assistance.<br/>

### Day 072 - College Major vs Your Salary Analysis

This project involves analyzing the post-university salaries of graduates by major. 

**Learning Points**

- Use `.head()`, `.tail()`, `.shape` and `.columns` to explore your DataFrame and find out the number of rows and columns as well as the column names.
- Look for NaN (not a number) values with `.findna()` and consider using `.dropna()` to clean up your DataFrame.
- You can access entire columns of a DataFrame using the square bracket notation: `df['column name']` or` df[['column name 1', 'column name 2', 'column name 3']]`.
- You can access individual cells in a DataFrame by chaining square brackets `df['column name'][index]` or using `df['column name'].loc[index]`.
- The largest and smallest values, as well as their positions, can be found with methods like `.max()`, `.min()`, `.idxmax()` and `.idxmin()`.
- You can sort the DataFrame with `.sort_values()` and add new columns with` .insert()`.
- To create an Excel Style Pivot Table by grouping entries that belong to a particular category use the `.groupby()` method.

![College Major vs Your Salary Analysis](college-major-vs-your-salary/data-exploration-pandas-college-major.gif)

### Day 073 - Programming Languages

This project involves analyzing the popularity of different programming languages over time. Additionally, create beautiful charts using Matplotlib.

**Learning Points**

- Use `.groupby()` to explore the number of posts and entries per programming language.
- Convert strings to Datetime objects with `to_datetime()` for easier plotting.
- Reshape DataFrame by converting categories to columns using `.pivot()`.
- Use `.count()` and `isna().values.any()` to look for NaN values in our DataFrame, which we then replaced using `.fillna()`.
- Create (multiple) line charts using `.plot()` with a for-loop.
- Style charts by changing the size, the labels, and the upper and lower bounds of our axis.
- Add a legend to tell apart which line is which by color.
- Smooth out our time-series observations with `.rolling().mean()` and plot them to better identify trends over time.

![Programming Languages](programming-language/programming-languages.gif)

### Day 074 - LEGO Pieces

This project involves analyzing a dataset of LEGO Pieces.

**Learning Points**

- Use HTML Markdown in Notebooks, such as section headings `#` and how to embed images with the `<img>` tag.
- Combine the `groupby()` and `count()` functions to aggregate data.
- Use the `.value_counts()` function.
- Slice DataFrames using the square bracket notation e.g., `df[:-2]` or `df[:10]`.
- Use the `.agg()` function to run an operation on a particular column.
- `rename()` columns of DataFrames.
- Create a line chart with two separate axes to visualise data that have different scales.
- Create a scatter plot in Matplotlib.
- Work with tables in a relational database by using primary and foreign keys.
- `.merge()` DataFrame along a particular column.
- Create a bar chart with Matplotlib.

![LEGO Pieces](analyze-the-lego-dataset/lego-analysis.gif)

### Day 075 - Google Trends

This project involves analyzing and combining Google Trends with other Time Series data.

**Learning Points**

- Use `.describe()` to quickly see some descriptive statistics at a glance.
- Use `.resample()` to make a time-series data comparable to another by changing the periodicity.
- Work with `matplotlib.dates` Locators to better style a timeline (e.g., an axis on a chart).
- Find the number of NaN values with `.isna().values.sum()`
- Change the resolution of a chart using the figure's `dpi`
- Create dashed `'--'` and dotted `'-.'` lines using `linestyles`
- Use different kinds of markers (e.g., `'o'` or `'^'`) on charts.
- Fine-tuning the styling of Matplotlib charts by using limits, labels, `linewidth` and colors (both in the form of named colors and HEX codes).
- Use `.grid()` to help visually identify seasonality in a time series.

![Google Trends](google-trends-data-analysis/google-trends-and-data-visualisation.gif)

### Day 076 - Android App Store

This project involves analyzing the Android App Store. Additionally, create beautiful charts using Plotly.

**Learning Points**

- Pull a random sample from a DataFrame using `.sample()`
- Find duplicate entries with `.duplicated()` and `.drop_duplicates()`
- Convert string and object data types into numbers with `.to_numeric()`
- Use Plotly to generate beautiful pie, donut, and bar charts as well as box and scatter plots.

![Android App Store](google-play-store-analysis/google-play-store-app-analytics.gif)

### Day 077 - Computation with Numpy

This project involves computing numerical data using the Numpy python library.

**Learning Points**

- Create arrays manually with `np.array()`
- Generate arrays using  `.arange()`, `.random()`, and `.linspace()`
- Analyse the shape and dimensions of a ndarray
- Slice and subset a ndarray based on its indices
- Do linear algebra like operations with scalars and matrix multiplication
- Use NumPy’s broadcasting to make ndarray shapes compatible
- Manipulate images in the form of ndarrays

![Computation with Numpy](computation-with-numpy-and-n-dimensional-array/computation-with-numpy.gif)  

### Day 078 - Movie Budget and Financial Performance

This project involves analyzing the Movie Budget and Financial Performance data. Additionally, run a linear regression on the data using scikit-learn. Finally, create beautiful charts using Seaborn.

**Learning Points**

- Use nested loops to remove unwanted characters from multiple columns
- Filter Pandas DataFrames based on multiple conditions using both `.loc[]` and `.query()`
- Create bubble charts using the Seaborn Library
- Style Seaborn charts using the pre-built styles and by modifying Matplotlib parameters
- Use floor division (i.e., integer division) to convert years to decades
- Use Seaborn to superimpose a linear regressions over our data
- Make a judgement if our regression is good or bad based on how well the model fits our data and the r-squared metric
- Run regressions with scikit-learn and calculate the coefficients.

![Movie Budget and Financial Performance](movie-budget-and-financial-performance-analysis/seaborn-and-linear-regression.gif)  


### Day 079 - Nobel Prize

This project involves analyzing the Nobel Prize data. Additionally, create beautiful charts using Matplotlib, Plotly and Seaborn.

**Learning Points**

- Uncover and investigate NaN values.
- Convert objects and string data types to numbers.
- Create donut and bar charts with Plotly.
- Create a rolling average to smooth out time-series data and show a trend.
- Use `.value_counts()`, `.groupby()`, `.merge()`, `.sort_values()` and `.agg()`.
- Create a Choropleth to display data on a map.
- Create bar charts showing different segments of the data with plotly.
- Create Sunburst charts with plotly.
- Use Seaborn's `.lmplot()` and show best-fit lines across multiple categories using the `row`, `hue`, and `lowess` parameters.
- Understand how a different picture emerges when looking at the same data in different ways (e.g., box plots vs a time series analysis).
- See the distribution of our data and visualise descriptive statistics with the help of a histogram in Seaborn.

![Nobel Prize](nobel-prize-analysis/nobel-prize-analysis.gif)  

### Day 080 - Dr. Semmelweis Handwashing

This project involves analyzing the collected data on the number of births and maternal deaths at Vienna General Hospital throughtout the 1840s.

**Learning Points**

- Use histograms to visualise distributions
- Superimpose histograms on top of each other even when the data series have different lengths
- Use a to smooth out kinks in a histogram and visualise a distribution with a Kernel Density Estimate (KDE)
- Improve a KDE by specifying boundaries on the estimates
- Use `scipy` and test for statistical significance by looking at p-values.
- Highlight different parts of a time series chart in Matplotlib.
- Add and configure a Legend in Matplotlib.
- Use NumPy's `.where()` function to process elements depending on a condition.

![Dr. Semmelweis Handwashing](dr-semmesweis-handwashing-analysis/dr-semmelweis-handwashing-discovery.gif)  

### Day 081 - Predict Boston House Prices

This project involves analyzing the Boston house price data and building a model to estimate house prices using that data.

**Learning Points**

- Spot relationships in a dataset using Seaborn's `.pairplot()`.
- Split the data into a training and testing dataset to better evaluate a model's performance.
- Run a multivariable regression.
- Evaluate that regression-based on the sign of its coefficients.
- Analyze and look for patterns in a model's residuals.
- Improve a regression model using (a log) data transformation.
- Specify values for various features and use model to make a prediction.

![Predict Boston House Prices](predict-boston-house-prices/multivariable-regression-and-valuation-model.gif)  

## Getting Started

### Set Up for Data Science

<b>Download and add the Notebook to Google Drive</b>
<br/> 

Add the .ipynb file into your Google Drive and open it as a Google Colaboratory notebook.


<b>Add the Data to the Notebook</b>
<br/> 

Add the .csv files to your Google Colaboratory notebook.

## Built With
<p>
  <img alt="Python" src="https://img.shields.io/badge/-Python-ffde57?style=flat-square&logo=python&logoColor=#4584b6" />
  <img alt="Pandas" src="https://img.shields.io/badge/-Pandas-4848b6?style=flat-square&logo=pandas&logoColor=white" />
  <img alt="NumPy" src="https://img.shields.io/badge/-NumPy-7099f7?style=flat-square&logo=numpy&logoColor=4848b6" />
  <img alt="Plotly" src="https://img.shields.io/badge/-Plotly-000000?style=flat-square&logo=plotly&logoColor=white" />
  <img alt="sciket-learn" src="https://img.shields.io/badge/-scikit%20learn-EC471A?style=flat-square&logo=scikit-learn&logoColor=1E81FB" />
  <img alt="Obsidian" src="https://img.shields.io/badge/Obsidian-7E1DFB?style=flat-square&logo=obsidian&logoColor=white" />
  <img alt="git" src="https://img.shields.io/badge/-Git-f34f29?style=flat-square&logo=git&logoColor=white" />
  <img alt="Github" src="https://img.shields.io/badge/-Github-14232c?style=flat-square&logo=github&logoColor=white" />
</p>

## Authors

*Initial work* - [grandeurkoe](https://github.com/grandeurkoe)

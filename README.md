# Fundamentals of Data Analysis Project 2019: Exploring the 'Tips' Dataset


![tip-jar](https://user-images.githubusercontent.com/47186083/68902310-de244e00-072f-11ea-83c9-0205dbbaf18a.jpg)

In this repository you will find my work on the project for the module Fundamentals of Data Analysis at GMIT.
I have done research on the tips dataset and created a Juputer Notebook with my findings.
First I have described the dataset, then I have looked at the correlation between the total bill and the tip, and in the last section I have looked at the relationships between the other variables.

## Getting started

Follow these steps to download this repository:

- Go to my repository on Github: https://github.com/Ardvb/FODAProject2019
- Click the clone or download button.
- Save the repository to your device.
- To run the program open a command interface and navigate to the folder in which the repository was saved.
- The full 'tips' dataset can be downloaded here: https://www.kaggle.com/ranjeetjain3/seaborn-tips-dataset

## Running my Jupiter Notebook
- Navigate to the folder where the repository has been downloaded on the command line.
- typ: Jupyter Notebook
- From the 'home' page, click on the file called 'FODA Assessment 2019.ipynb'
- For more information on how to use Jupyter Notebook go to the Help section in the toolbar on the top of your screen.

## Background information on the dataset
In one restaurant, a food server recorded the following data on all customers they served during an interval of two and a half months in early 1990. The restaurant, located in a suburban shopping mall, was part of a national chain and served a varied menu. In observance of local law, the restaurant offered to seat in a non-smoking section to patrons who requested it. Each record includes a day and time, and taken together, they show the server’s work schedule. 7 variables were recorded in this dataset: tip, total bill, sex, day, time, size and smoker.  (Partly taken from: https://www.kaggle.com/ranjeetjain3/seaborn-tips-dataset)

## Packages used

### - Numpy 
Numpy is a fundamental library for scientific computing in Python. It adds support for large, multi dimensional arrays and matrices. It also includes a large collection of high level mathematical functions to operate on these arrays.
### - Seaborn
Seaborn is a Python visualization library based on matplotlib, providing a high-level interface for drawing statistical graphics. I found this library to be easy to use and used it to plot swarmplots and scatterplots.
### - Matplotlib
Matplotlib is the plotting library of Numpy. It provides an object-oriented API for embedding plots into applications. I used this library to plot histograms, amongst other things.
### - Pandas
Pandas is a library providing high-performance, and easily usable data structures and data analysis tools for Python. It is built on top of Numpy, so that means Numpy is required by Pandas. I have used it to read in the excel file containing the Iris date set, amongst other things.


## References
https://www.kaggle.com/ranjeetjain3/seaborn-tips-dataset

References
How to suppress warnings in Jupyter Notebook: https://exploredatalab.com/how-to-suppress-warnings-in-jupyter-notebook/
How to count the occurences of a specific value using Pandas: https://stackoverflow.com/questions/35277075/python-pandas-counting-the-occurrences-of-a-specific-value
How to plot a pie chart using matplotlib: https://pythonspot.com/matplotlib-pie-chart/
How to count frequency of a value in a column: https://stackoverflow.com/questions/22391433/count-the-frequency-that-a-value-occurs-in-a-dataframe-column/36434248
How to group data by certain values using Pandas: https://www.geeksforgeeks.org/pandas-groupby/
How to plot a relplot with Seaborn: https://seaborn.pydata.org/generated/seaborn.relplot.html
How to plot a lmplot using Seaborn: https://seaborn.pydata.org/generated/seaborn.lmplot.html
How to generate polyfit using Numpy: https://docs.scipy.org/doc/numpy/reference/generated/numpy.polyfit.html
How to divide two columns in a dataframe: https://stackoverflow.com/questions/36619631/how-to-divide-two-column-in-a-dataframe
How to select rows between 2 values using pandas: https://stackoverflow.com/questions/31617845/how-to-select-rows-in-a-dataframe-between-two-values-in-python-pandas/40442778
How to add a title to Seaborn plot: https://stackoverflow.com/questions/29813694/how-to-add-a-title-to-seaborn-facet-plot
How to plot a bar chart using Matplotlib: https://pythonspot.com/matplotlib-bar-chart/
How to plot a pairplot using Seaborn: https://seaborn.pydata.org/generated/seaborn.pairplot.html
How to plot categorical data: https://seaborn.pydata.org/tutorial/categorical.html
How to use Pandas' .loc function to extract rows https://www.geeksforgeeks.org/python-pandas-extracting-rows-using-loc/
How to implement a boolean search with multiple columns using Pandas: https://stackoverflow.com/questions/22546425/how-to-implement-a-boolean-search-with-multiple-columns-in-pandas

Videolectures:

Videolecture Ian McLoughlin about best fit line: https://web.microsoftstream.com/video/021a0f49-a019-4119-a08c-7601a9a7d0b5
Videolecture Ian McLoughlin about using Pandas to calculate descriptive statistics: https://web.microsoftstream.com/video/ecc9ce4a-c6f5-4c50-a4f4-29116fc21b81?referrer=https://learnonline.gmit.ie/course/view.php?id=689

Image: 

https://www.daddysqueeze.com/tips/

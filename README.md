# IP-WEEK-7
This document contains the project done on Exploratory data analysis, Univariate, Bivariate and Multivariate

Univariate Analysis

Univariate analysis is the simplest of the three analyses where the data you are analyzing is only one variable. There are many different ways people use univariate analysis. The most common univariate analysis is checking the central tendency (mean, median and mode), the range, the maximum and minimum values, and standard deviation of a variable.
Common visual technique used for univariate analysis is a histogram, which is a frequency distribution graph. You could also use a box plot or violin plot to compare the spread of the variables and provides an insight into outliers. Using any of the above mentioned to compare the “Has a bank account” in the Finance dataset across citizens is only comparing one variable, therefore a Univariate analysis.

Bivariate Analysis

Bivariate analysis is where you are comparing two variables to study their relationships. These variables could be dependent or independent to each other. In Bivariate analysis is that there is always a Y-value for each X-value.
The most common visual technique for bivariate analysis is a scatter plot, where one variable is on the x-axis and the other on the y-axis. In addition to the scatter plot, regression plot and correlation coefficient are also frequently used to study the relationship of the variables. For example, continuing with the Finance dataset, you can compare “Has a bank account” vs “Gender” or “Has a bank account” vs the “location”to see if there is a relationship.

Multivariate Analysis

Multivariate analysis is similar to Bivariate analysis but you are comparing more than two variables. For three variables, you can create a 3-D model to study the relationship (also known as Trivariate Analysis). However, since we cannot visualize anything above the third dimension, we often rely on other softwares and techniques for us to be able to grasp the relationship in the data.
In terms of visualization, Seaborn library in Python allows for pairplots where it generates one large chart of selected variables against one another in a series of scatter plots and histograms depending on the type of variable, also known as scatter plot matrix. 

Depending on the dataset and the depth of analysis required, there are other techniques that you could deploy, such as Principal Component Analysis or logistic regression, linear regression, cluster analysis, dimensionality reduction, factor analysis etc.

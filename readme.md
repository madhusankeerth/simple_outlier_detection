# Simple Outlier Detection

The purpose of this project is to compute and visualize outliers in a time series, while preprocessing and aggregating the underlying raw data.

## Required Data Files

Please downlod the raw data file (**train.gz**) before running this project from Kaggle Competetion here: [train.gz](https://www.kaggle.com/c/avazu-ctr-prediction/data).

## Required Libraries

Pandas, Numpy, Matplotlib, Seaborn and Bokeh.

## Structure

####  Import Libraries
We import necessary libraries.

####  Data Preprocessing
We read the data into a dataframe and perform the necessary data cleaning, formatting, aggregation to compute the Click-Through-Rate (CTR) for the time series.

####  Functions
We define some functions to help us compute the moving average/standard deviation and plot the time series.

####  Outlier Detection
We use the functions defined above to identify the outliers based on user-input criteria.

####  Visualizing Outliers
We visualize the identified outliers on the CTR time-series interactive graph.


## Author

Madhu Sankeerth: [GitHub](https://github.com/madhusankeerth)


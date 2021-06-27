# EDA-for-COVID-dataset
Exploratory Data analysis for COVID cases in italy according to regions.

In this project , I have performed Exploratory Data analysis on COVID data for italy regions. I have collected this data from WHO website , this data might not be the latest one. You can check for the latest data in WHO website.

ABOUT THE DATA :

There are a total of 21 regions in italy , there are 6027 rows 17 columns in this dataset. All the columns are cumilative Except for New positive cases column. 
This is a time series data , But I have not used typical time series anlysing techniques on it. I have just tried to visualize all the columns and see how each column is correlated.

LIBRARIES :

I have used Seaborn , matplotlib and plotly for visualization the data.

TESTS PERFORMED :

After the visualization , To get an inference about the data , I performed F-test in order to see whether the mean of the new positive cases in all regions is same or not. 
Since the p-value accuried in the test in much greater that 0.5 , I rejected null hypothesis i.e The mean of new positive cases in each region is not equal.

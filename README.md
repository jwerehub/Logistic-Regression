# Logistic-Regression

In this project, I have attempted to create a Linear Regression Model. I am implementing it using sklearn which is the most common machine learning library.

Libraries used in this project
I have installed Anaconda for this project. It has most of the libraries installed hence making work easier.
The libraries i have used are; 
-pandas to enable data manipulation and storage
-numpy to provide functions to operate. 
-matplotlib ro provide plotting tools. 
-NumpyIt provides a fast numerical array structure and operating functions.


Loading the data
I loaded my data using dataset.pd_csv(). I proceeded to check the first and last data values using dataset.head() and dataset.tail() functions respectively.

Checking for duplicated data
I used the function dataset.duplicated() to see if there is any data duplicated. i found that there was no duplicate values in my data.

Describing data
I used the dataset.describe() function to describe the data, including getting the mean .

Checking for unique data
For this, I used dataset.nunique to display unique data there.

Cleaning data
To make sure that there were no anomalies, I used the function dataset.isnull().sum() to add up any anomalies that may be present. However, my data was clean so I proceeded to the next step.

Finding correlation of data.
I proceeded to use the function dataset.corr() which shows us the correlation between the categories in our dataset which was age, bmi and the charges.

Creating the heatmap
Heatmaps are great for visualizing data in a colourful manner, while showing us correlation between the variables. To do this, use the function sns.heatmap(dataset.corr()).

Making the pairplot.
This is also a great way to visualize our data. I used the code sns.pairplot(dataset.corr()) and it should plot our variables.

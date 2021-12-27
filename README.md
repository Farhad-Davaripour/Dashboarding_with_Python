## Hands-on Practice Learning Lab for Data Science

![image](Dashboard.png)

### Overview
* * *
This repository presents a step by step approach for data wrangling, descriptive statistical analysis, predictive analysis, model development, model evaluation, and decision making. This project is a part of [Data Analysis with Python](https://www.coursera.org/learn/data-analysis-with-python?) course offered by [Coursera.org](https://www.coursera.org/). The dataset includes auto info provided in the course and could be downloaded from IBM cloud.

✓ Link to the dataset: [Link](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/Data%20files/auto.csv)  
✓ link to the description of each column of the dataset [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.names)  
✓ Link to the notebook: [Link](https://github.com/Farhad-Davaripour/Descriptive_Statistical_Analysis_Auto_Dataset/blob/main/Code_Python.ipynb)   

In this study:

1) the following steps are carried out to address the missing values in the dataset, including:
* replacing the missing values (? in here) with np.nan
* finding the columns which include missing values and counting the number of elements with missing values
* replacing the missing values with the average of the values in the column  

2) the following steps are taken in order to prepare the data for data analysis:
* normalizing the values based on the (value - average(column))/standard_deviation(column)
* binning the columns into categorical groups (e.g., low, medium, and high)
* Turning categorical variables into quantitative variables (e.g., 0 and 1)

3) statistical descriptive analyses are performed using:
* Chi-Square and analysis of variance (ANOVA) methods for columns with object data type
* Pearsonr method for columns with numerical data type

4) In_sample testing:
* splitting the data into train and test data with test data include 30% of the overall data

5) model development is performed using:
* Simple linear regression model
* Multi-linear regression model
* 1-dimensional polynomial regression model
* Multi-dimensional polynomial regression model

6) model evaluation and decision making is carried out using the following statistical methods:
* Mean Square Error (MSE)
* R-Square
  


## About The Author

![image](MyImage-GitHub.jpg)


- Farhad Davaripour is a numerical scientist with 3 years of experience working in research and development roles. He has a knack for problem-solving and passion for data science (He is in training).
- Currently He is taking the data science fundamental courses as a part of IBM Data Science Professional Certificate. 
- Connect with Farhad on [LinkedIn](https://www.linkedin.com/in/farhad-davaripour/)

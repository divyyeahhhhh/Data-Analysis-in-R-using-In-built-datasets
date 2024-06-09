# Data-Analysis-in-R-using-In-built-datasets
## Exploratory Data Analysis (EDA) on the Iris Dataset
The Iris dataset is a classic dataset used frequently in data mining and machine learning courses. It includes measurements of 50 samples from each of three species of Iris flowers: Iris setosa, Iris virginica, and Iris versicolor. Each sample has four features: sepal length, sepal width, petal length, and petal width, all measured in centimeters. This analysis will perform several exploratory data analysis (EDA) steps on the Iris dataset.

## Step-by-Step EDA
### (i) Dimension, Structure, Summary Statistics, and Standard Deviation of All Features
**1.) Dimensions:**
-  _The Iris dataset has 150 rows and 5 columns (4 features + 1 species label)._ 

**2.) Structure:**
- _The dataset contains both numerical and categorical data._
- _FEATURE:Sepal.Length, Sepal.Width, Petal.Length, Petal.Width._
- _Categorical variable: Species._

**3.)Summary Statistics:**

- _Includes measures like mean, median, minimum, maximum, and quartiles for all numerical features._

**4.)Standard Deviation:**
- _Standard deviation of each feature to understand the dispersion of the data._
  
### (ii) Mean and Standard Deviation of Features Grouped by Species
- _Compute the mean and standard deviation of each feature (Sepal.Length, Sepal.Width, Petal.Length, and Petal.Width) for each species of Iris flowers (Iris setosa, Iris virginica, and Iris versicolor)._
### (iii) Quantile Values of Sepal Width and Length
- _Calculate the quantile values (e.g., 25th, 50th, 75th percentiles) for Sepal.Length and Sepal.Width._
### (iv) Creating a New Data Frame with a Sepal Length Category
**1.)New Column:**
- _Create a new data frame named iris1 with an additional column Sepal.Length.Cate._
- _Sepal.Length.Cate categorizes Sepal.Length based on its quantiles (e.g., low, medium, high)._
### (v) Average Value of Numerical Variables by Species and Sepal Length Category
- _Calculate the average value of numerical features grouped by the two categorical variables: Species and Sepal.Length.Cate._
### (vi) Average Mean Value of Numerical Variables by Species and Sepal Length Category
- _Calculate the mean value of numerical features grouped by Species and Sepal.Length.Cate._
### (vii) Creating a Pivot Table
- _Create a pivot table that summarizes the data based on Species and Sepal.Length.Cate._
- _This table will help in understanding the interaction between species and the categorized sepal length._

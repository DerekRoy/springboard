# Springboard Data Science Bootcamp
This repository houses the projects I completed while attending (Springboard's Data Science Career Track Bootcamp)[https://www.springboard.com/workshops/data-science-career-track]. Below is a list of projects with descriptions and links.

## Capstone 1: [Predicting the Neighborhood-level Prevalence of Chronic Kidney Disease](predicting_chronic_disease)
In this project data was collected from the CDC and U.S. Census Bureau API (nearly 400 features on 28,000 census tracts from the 500 largest cities in the United States) to predict the prevalence of chronic kidney disease (CKD). Predicting neighborhood-level prevalence may help to reduce the personal and economic costs of CKD by creating highly targeted public health campaigns.

**Key Skills**

* Data wrangling and cleaning
* Exploratory Data Analysis
* Inferential Statistics
* Data Visualization (including data maps)

**Data Sources**

* [500 Cities: Local Data for Better Health (Centers for Disease Control)](https://catalog.data.gov/dataset/500-cities-local-data-for-better-health-b32fd)
* [American Community Survey 5-year Data API (U.S. Census Bureau)](https://www.census.gov/data/developers/data-sets/acs-5year.html)

![CKD prevelance in two Indiana cities](predicting_chronic_disease/img/two_cities.png)

## Capstone 2


## Mini-projects
### [Customer Segmentation with Unsupervised Learning](clustering)
With a dataset detailing marketing email campaigns and another with customer sales data, the objective was to segment the customer base to gain insight into customer behavior. The analysis can then be used to tailor future marketing campaigns to exsisting and potential clients. 

**Key Skills**

* `scikit-learn` to implement clustering with:
    * K-means
    * Affinity Propagation
    * Spectral Clustering
    * Agglomerative Clustering
    * DBSCAN
* evaluate clustering with unsupervised metrics
    * Silhouette Score
    * Calinski-Harabaz Score
    * Gap Statistic
* visualize clustering with PCA dimension reduction and tSNE


![tSNE 2D map of customers](clustering/tsne_map.png)

### [Using Logistic Regression to Determine Sex based on Height and Weight](logistic_regression)
This project focused on the mathematics of logistic regression and used `scikit-learn` for implementation. Grid search was used to improve the model through hyperparameter tuning.

**Key Skills**

* use `scikit-learn` to implement logistic regression model
* use `GridSearchCV` to optimize hyperparameter tuning
* gain visual understanding of logistic regression model using plots

![Deterministic Probabilities](logistic_regression/logreg_prob.png)

### [Predicting Housing Prices with Linear Regression](linear_regression)
Using the Boston Housing Data Set, this mini-project applies linear regression with the `statsmodels` and `scikit-learn` libraries to create and compare predictive models. 

**Key Skills**

* linear regression (univariate and multivariate)
* model interpretation
* model evaluation with sum-of-squares, R<sup>2</sup>, mean squared error, and F-statistic
* fine-tuning models using influence and residual plots
* comparing models with F-statistic and AIC
![influence plot](linear_regression/images/influence_plot.png)

### [Reducing Hospital Readmission Rates](EDA_hospital_readmission)
This mini-project uses statistics and data visualization to analyze the potential efficacy of proposed measures for reducing excess readmission ratios for U.S. hospitals. 

**Key Skills**

* pairs bootstrap / frequentist statistical analysis
* hypothesis testing with difference of means, Pearson's r, and linear regression slopes
* data visualization using seaborn and matplotlib

![scatter plot with subgroup means](EDA_hospital_readmission/img/scatterplot_w_means.png)

### [Examining Racial Discrimination in the U.S. Job Market](EDA_racial_discrimination)
Statistical analysis was used to determine if their is racial bias toward job applicants with White-sounding names.

**Key Skills**

* bootstrap / frequentists statistical analysis
* hypothesis testing with two-sample inference
* pandas | seaborn | matplotlib

![Distributions of the Difference of Means](EDA_racial_discrimination/img/diff_of_means_distros.png)

### [Analyzing Human Body Temperature](EDA_human_temperature)
This mini-project used statistical analysis to determine if 98.6<sup>o</sup>F is actually the average human body temperature.

**Key Skills**

* bootstrap / frequentists statistical analysis
* hypothesis testing with one-sample inference
* pandas | seaborn | matplotlib

### [Quandl Financial Data API](API)
Pull financial data from the Quandl API in order to calculate descriptive statistics.

**Key Skills**
* using `requests` library to access API
* descriptive statistics

### [SQL Mini-Project](sql_mini_project.sql)
This project utilized a SQL query script to pull data from a fictional facilities dataframe

**Key Skills**
* SQL / MySQL queries

### [Wrangling World Bank Data with JSON](data_wrangling_json)
Pull data from a JSON file into Python to generate descriptive statistics.

**Key Skills**
* reading JSON files directly into pandas
* descriptive statistics
* data visualization with pandas

## Interview Prep
These are series of questions that were given at the end of each unit.

**[Inferential Statistics](interview_prep/inferential_statistics.md)**: <br />
General questions about statistics and methods of hypothesis testing.

**[Data Wrangling](interview_prep/data_wrangling.md)**:<br />
Questions about using pandas and SQL for data wrangling.

**[Programming Boot-up](interview_prep/programming_boot-up.md)**:<br />
General questions about python data structures and standard libraries.



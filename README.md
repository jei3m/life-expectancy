# Life Expectancy Prediction

The project aims to analyze and predict life expectancy at birth, which reflects the average number of years a newborn infant would live if current mortality trends persist throughout their lifetime. By utilizing a variety of data science techniques, including Linear Regression, Decision Trees, Random Forest, and Support Vector Machines (SVM), the project will explore historical life expectancy data derived from multiple authoritative sources such as the United Nations Population Division, Eurostat, and national statistical offices.

## About the Dataset
The dataset was obtained from [https://fred.stlouisfed.org/series/SPDYNLE00INUSA]. It has 2 Columns, one is the date born and the other is the number of year lived. The data is derived from male and female life expectancy at birth from sources such as, United Nations Population Division, World Population Prospects, United Nations Statistical Division, Population and Vital Statistics Report (various years), Census reports and other statistical publications from national statistical offices, Eurostat: Demographic Statistics, Secretariat of the Pacific Community: Statistics and Demography Program, and U.S. Census Bureau: International Database.

Note: The Month and Day of the dataset are all January 1 for a more accurate comparison, the only difference that they have is the year born

## Dataset Snapshot
The following table shows a snapshot of the dataset used in this project:
 >Date: Represents the date born.
 >SPDYNLE00INUSA: Represents the life expectancy.

## Data Preprocessing
In the Data Preprocessing first the data was checked for null values, on the Year column it was changed to only the year since the values of the month and day are the same. Which is why only the year is reflected in the Year column.

## Model Development
To predict life expectancy, we utelized four models: Linear Regression (with polynomial features), Decision Tree, Random Forest, and Support Vector Regressor. The data was standardized, and models were trained to capture life expectancy trends. Performance was evaluated using MSE and R² metrics to compare each model’s predictive accuracy. This approach ensured a balance between model complexity and accuracy in capturing the trend.
## Model Evaluation

The table below shows the evaluation of the models

| Model Name            |   MSE  |   R2   |
| :-------------------- | -------|--------|
| Linear Regression     | 0.9611 | 0.9018 |  
| Decision Tree         | 0.4162 | 0.9575 |
| Random Forest         | 0.3896 | 0.9602 |
| Support Vector Machine| 0.4085 | 0.9583 |

## Conclusion


## Contributors# life-expectancy
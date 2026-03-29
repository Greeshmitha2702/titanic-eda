# Titanic Dataset - Exploratory Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Seaborn Titanic dataset to understand survival patterns and key factors linked to passenger outcomes.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## EDA Steps
- Data loading
- Basic structure check (`shape`, `info`, `describe`)
- Missing-value inspection
- Data visualization
- Correlation analysis
- Groupby analysis
- Insights

## Analyses Completed
- Displayed dataset preview using `head()` and `tail()`
- Checked dataset shape, column types, and summary statistics
- Checked missing values column-wise
- Count plot of male vs female passengers
- Sex-wise survival count plot
- Class-wise survival count plot
- Point plot for mean age by passenger class
- Correlation heatmap between numeric class mapping (`class_num`) and `fare`
- Age distribution histogram
- Grouped survival analysis by age
- Survival-rate comparison for solo vs non-solo travelers

## Key Insights So Far
- Females show higher survival compared to males
- First-class passengers show better survival than lower classes
- Fare and class are related, and higher fares are associated with higher survival groups
- Most passengers are in the 20-40 age range
- Younger passengers (especially children) tend to have better survival outcomes
- Traveling status (`alone`) shows a measurable difference in survival between solo and non-solo passengers

## Conclusion
EDA has identified meaningful survival patterns by sex, class, age, fare, and travel status. These findings form a strong base for feature engineering and predictive modeling.
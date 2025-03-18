# Walmart-Customer-Purchased-Analysis

## Business Problem
The management team at Walmart Inc. aims to analyze customer purchase behavior, specifically the purchase amount, against customer gender and various other factors. The primary focus is on understanding if spending habits differ between male and female customers during Black Friday. With an assumption of 50 million male and 50 million female customers, the goal is to provide insights that can aid in making informed business decisions.

## Approach

### Import and Data Analysis:
Import the dataset and conduct a thorough analysis of its structure and characteristics.
Detect null values and outliers using techniques such as boxplots, the "describe" method, and checking the difference between mean and median.
### Data Exploration:
Track the amount spent per transaction for both 50 million female and 50 million male customers.
Calculate the average spending for each gender and draw conclusions based on the results.
### Confidence Interval Calculation:
Use bootstrapping to estimate the confidence interval of the population mean of expenses for both female and male customers.
Apply the Central Limit Theorem to compute intervals, exploring various confidence levels (90%, 95%, and 99%).
### Comparison Across Demographics:
Extend the analysis to compare spending based on marital status and age groups (binned into life stages).
Provide recommendations and action items for Walmart based on the findings.
### Dataset Description
Features include User_ID, Product_ID, Gender, Age, Occupation, City_Category, StayInCurrentCityYears, Marital_Status, ProductCategory, and Purchase. Categorical columns: Gender, Occupation, City_Category, Marital_Status, and Product_Category. Observations: No nested data.

## Observations from EDA
Majority of entries are for male gender, and the top age bin is 26-35.
City_Category B has the highest frequency, and most customers stay in the current city for one year.
Average purchase amount is 9263, with a high standard deviation of 5023.
## Statistical Analysis (Using CLT & CI)
Confidence intervals for mean purchase amounts by gender show clear distinctions with increasing sample size.
Overlapping is observed but increases with a higher confidence interval.
Similar analyses are conducted for marital status and age groups, providing insights into spending patterns.
## Recommendations
### Gender-Based:
Implement targeted offers for women to increase spending during Black Friday.
### Age-Based:
Introduce games or special promotions to attract a younger audience and boost sales.
### Overall:
Consider tailored strategies for different demographics to enhance the shopping experience and drive sales.
## Conclusion
The analysis provides valuable insights into customer spending patterns, allowing Walmart to tailor its approach for different demographic segments and optimize sales strategies.

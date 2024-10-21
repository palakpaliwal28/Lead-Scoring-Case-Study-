# Problem Statement

Company - X Education sells online courses to industry professionals.
Challenge - Low lead conversion rate (30%) despite acquiring many leads daily.
Goal - Identify 'Hot Leads' to improve conversion rates to around 80%.
Data - A dataset of approximately 9,000 leads with various attributes, including a target variable 'Converted' (1 for converted, 0 for not).
Objective - Build a logistic regression model to assign lead scores, focusing on key variables and categorical factors for better targeting.

# Summary
This analysis seeks to identify the key factors that influence industry
professionals' decisions to enroll in X Education's courses. By examining
website interactions, engagement patterns, and demographic characteristics,
we can formulate targeted strategies to enhance conversion rates.

## Methodology
Data Cleaning: We addressed missing values and replaced irrelevant
options with null values to improve data quality.
1. Exploratory Data Analysis (EDA):
   Initial EDA indicated that categorical
variables contained irrelevant elements, while numeric values were sound
without outliers.
3. Feature Engineering:
   We created dummy variables, eliminated those with
'not provided' elements, and applied MinMaxScaler to numeric values.
5. Train-Test Split:
   The dataset was divided into 70% for training and 30% for
testing.
7. Model Building:
   We used Recursive Feature Elimination (RFE) to identify the
top 15 relevant variables, removing others based on Variance Inflation Factor
(VIF) and p-values.
9. Model Evaluation:
     A confusion matrix was constructed, and the optimal
cutoff value was determined using the ROC curve, achieving around 80%
accuracy.
11. Key Findings
    1. Total Time Spent on Website: Longer engagement indicates higher interest.
    2. Total Number of Visits: Frequent visits suggest strong purchase intent.
    3. Lead Source: Google and direct traffic are most effective.
    4. Last Activity: Recent interactions reflect current interest.
    5. Lead Origin: Certain formats yield higher conversion rates.
    6. Current Occupation: Working professionals are more likely to invest in
courses.

Focusing on these variables can enhance X Education's marketing strategies
and drive business growth.


This Assignment is done by Palak Paliwal, Jaya Vineela Pasupuleti, Parimalmanoj Varanasi


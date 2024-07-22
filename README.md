# Analyzing Flight Delay Patterns in 2006 and 2007

## Objective
The project aims to analyze flight delay patterns using data from January 2006 to December 2007. The study focuses on identifying trends, causes of delays, and predicting future delays using machine learning techniques.

### Skills Learned
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Machine Learning Model Development and Evaluation
- Data Visualization

### Tools Used
- Python
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

## Steps
1. Data Wrangling

The data was sourced from the Harvard Dataverse and included flight details for 2006 and 2007. Key steps in data wrangling included:
- Importing necessary libraries: numpy, pandas, scikit-learn, seaborn, matplotlib
- Reading and combining datasets using read.csv and concat from pandas
- Creating new columns for date and delay calculations
- Cleaning data to ensure consistency and accuracy

2. Exploratory Data Analysis (EDA)
- EDA was performed to uncover insights into the flight delay data, including:

3. Distribution of delays
- Trends in the number of flights over time
- Reasons for flight cancellations
- Correlation between different variables and delays

4. Machine Learning

A machine learning model was developed to predict flight delays. Steps included:
- Constructing a correlation matrix to avoid multicollinearity
- Using Linear Regression to model the relationship between variables and flight delays
- Evaluating the model with metrics such as R-squared, F1-score, and Mean Squared Error

## Conclusion
The analysis provided several key insights, such as:

- Most flights experienced little or no delay
- Carrier delays were the primary cause of delays
- Optimal times to fly to minimize delays include early mornings, Saturdays, and November
- Older planes tend to experience more delays
These findings can help airlines improve operations and reduce delays, ultimately enhancing passenger satisfaction.



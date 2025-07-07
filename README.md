# A/B Testing Analysis: Marketing Campaign Effectiveness
## 1. Project Description
This project performs an A/B test analysis to evaluate the effectiveness of a test marketing campaign versus a control campaign. The goal is to determine whether the test variant leads to significantly higher conversion rate, click-through rate, and lower cost per conversion using robust statistical methods.

## 2.  Key Sections
  #### a. Data Cleaning: Imported and cleaned raw data for analysis
  #### b. Exploratory Analysis: Visualized campaign engagement 
  #### c. Feature Engineering: Created key metrics 
  #### d. Hypothesis Testing: Applied Welch's t-test and two sample t-test to compare campaign performance

## 3. Hypothesis
Three key metrics were statistically analyzed to evaluate the impact of the test campaign:

#### Conversion Rate :
     Welch’s t-test used to compare mean conversion rates between test and control groups.

#### Click-Through Rate (CTR) :
     A two-sample Welch’s t-test evaluated whether user engagement varied significantly across campaigns.

#### Cost Per Conversion :
     Mann-Whitney U test (non-parametric) evaluated cost-efficiency across campaigns.

All tests were designed to detect whether the test campaign produced a statistically significant change—regardless of direction—compared to the control.

## 4. Tech Stack
Python

Pandas, NumPy

Matplotlib, Seaborn

SciPy for statistical tests



Predicting Employee Churn



Project Overview

This notebook explores a dataset of employee engagement and workplace satisfaction to better understand what drives voluntary attrition. After loading and cleaning the data, I used exploratory analysis to investigate how factors like satisfaction, overtime, and travel frequency relate to employee churn. The goal was to identify early signals of disengagement so organizations can take proactive steps to retain talent.



Methods & Results

I trained a logistic regression model to predict whether an employee would leave, after preparing the data with dummy variables, binning, and handling missing values. The model's classification report and confusion matrix showed that it performed reasonably well, especially when adjusted for class imbalance. I also used model coefficients and odds ratios to interpret the impact of key features—highlighting that low job satisfaction, frequent travel, and working overtime were all strongly associated with higher churn likelihood. To deepen the analysis, I created interaction features (like combining satisfaction and travel frequency) and examined their average attrition rates to surface more nuanced patterns.



Key Outputs

Cleaned and encoded employee churn dataset

Visualizations of attrition by job satisfaction, overtime, income, and more

Logistic regression model with interpretability through coefficients

Confusion matrix and classification report to evaluate model performance

Feature interaction analysis to uncover compounded risk patterns



Conclusion

This project walks through a real-world churn modeling problem from start to finish—balancing technical tools with practical insight. With the help of logistic regression and interaction analysis, it highlights which workplace factors most influence employee retention and how HR teams can use data to support their people more effectively.


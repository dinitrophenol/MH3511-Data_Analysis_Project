## MH3511-Data Analysis Group Project 

With healthcare costs continuing to rise globally, understanding the factors that influence insurance claims is crucial for both insurers and policyholders. Insurance companies rely on accurate risk assessment to set premiums that reflect an individual’s likelihood of making a claim. It is known that certain factors like age, weight, smoking status and other pre-existing conditions reflect the risk of the policyholder which in turn affects the cost of their premiums. Thorough understanding of the relationship between the amount of claims and the various factors can provide valuable insights for risk assessment and policy pricing, ensuring appropriate premium pricing and maintaining its price competitiveness. Hence we aim to examine the relationship between insurance claims and the various demographic and health indicators through fundamental statistical analysis.

## Overview
This project investigates the factors that influence insurance claim amounts using a publicly available dataset. Through exploratory data analysis, statistical testing, and regression modelling, we identify key predictors of high insurance claims.

## Summary of Analysis
We explored the following key questions:
- Is the claim amount of an individual dependent on their attributes like their gender and age?
-How do specific health indicators such as BMI and blood pressure affect the claim amounts?
-Do the risk factors like smoking and diabetes affect the claim amounts?
-Which of the factors serves as the most important predictor for high insurance claims?
-What combination of variables are statistically significant in modelling insurance claims?

### Key Findings
- **Smoking** is the strongest individual predictor of higher claims
- **High blood pressure** and **BMI** (when exceeding clinical thresholds) are associated with higher claims
- **Age** and **diabetic status** do not significantly impact claim amounts
- A **multiple linear regression model** including smoking, blood pressure, BMI, children, region, and gender explains **55.4%** of the variance in claim amounts

## Tools Used
- **R** (Base R, ggplot2)
- Statistical techniques: correlation analysis, ANOVA, t-tests, linear regression

## Dataset Source
[Insurance Dataset on Kaggle] https://www.kaggle.com/datasets/thedevastator/insurance-claim-analysis-demographic-and-health/data4

## Contributors
- Victor [@VictorrFong](https://github.com/VictorrFong)
- Firdaus [@firkhannn](https://github.com/firkhannn)
- Thuva [@thuvathetuba](https://github.com/thuvathetuba)
- James [@jangasd](https://github.com/jangasd)
- Kent [@dinitrophenol](https://github.com/dinitrophenol)

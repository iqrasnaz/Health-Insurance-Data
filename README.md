# Health Insurance Data - Multiple Linear Regression in R

## **Project Overview:**

* Completed as a team project in a Regression Analysis course, this study explores how individual demographics and lifestyle choices impact medical insurance charges in the U.S. Using multiple linear regression in R, we modeled and interpreted cost-driving factors like age, BMI, and smoking status. The project also included diagnostic testing, variable transformation, and interaction terms to improve model accuracy and reliability. Our final model aimed to not only predict costs but also uncover insights for healthcare providers and insurance companies.

## **Objectives:**

* Predict individual medical insurance charges using a multiple linear regression model.
* Understand how key features such as age, BMI, smoking status, and number of children influence insurance costs.
* Validate regression assumptions and improve model performance through transformation and interaction terms.

## **Tools & Skills:**

* R (ggplot2, dplyr, lm)
* Multiple linear regression, Model diagnostics (multicollinearity, residuals, transformations), Data cleaning, feature engineering, and Exploratory Data Analysis
* Acknowledgment: Thank you to Kaggle for providing this public US Health Insurance dataset.

## **Data Summary:**

* Source: [kaggle](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset?resource=download)
* Size: 1338 rows of insured data & 7 columns (a mix of numeric and categorical variables, “charges” being the target variable)

## **Key Findings:**

* Smoking status, BMI, and age were significant predictors of insurance charges
* Smokers were charged significantly higher premiums compared to non-smokers.
* Interaction effects: A statistically significant interaction between BMI and smoker status revealed that the effect of BMI on charges was amplified for smokers.

* Multicollinearity was checked, and model assumptions were validated
* Log transformation of charges improved model fit (reduced skewness and improved residual normality)

## **Business Recommendations:**

* Insurance companies can use this model to better price policies based on risk factors
* Suggest targeted wellness incentives for smokers and individuals with high BMI to manage long-term costs

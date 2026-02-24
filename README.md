# Predictive-Analysis-Modelling
# 🏠 King County Housing Price Prediction

### Business Analytics \| Regression Modeling \| Real Estate Market Analysis

**Author:** Mrinal Mishra\
**Program:** MBA -- Business Analytics\
**Project Type:** End-to-End Data Analysis & Predictive Modeling

------------------------------------------------------------------------

## 🚀 Project Summary

Analyzed **21,613 real housing transactions** from King County,
Washington (May 2014 -- May 2015) to identify key drivers of home prices
and build a predictive regression model.

This project demonstrates strong skills in:

-   Data Cleaning & Transformation\
-   Feature Engineering\
-   Statistical Modeling\
-   Hypothesis Testing\
-   Business Insight Extraction\
-   Model Interpretation

------------------------------------------------------------------------

## 🎯 Business Objective

To answer:

> What factors significantly influence house prices in King County?

And build a regression model capable of explaining price variability
with strong statistical validity.

------------------------------------------------------------------------

## 📊 Dataset Overview

-   21,613 home sale records\
-   Real public transaction data\
-   20+ structured variables

### Key Feature Categories:

-   Structural: bedrooms, bathrooms, sqft_living, floors
-   Quality: grade, condition, view
-   Location: zipcode, latitude, longitude
-   Premium features: waterfront
-   Market timing: year sold
-   Neighborhood effect: sqft_living15

------------------------------------------------------------------------

## 🧹 Data Preparation

✔ Handled missing basement values (mean imputation)\
✔ Engineered binary renovation variable\
✔ Converted categorical variables into numeric groups\
✔ Created grouped variables for zip codes and build years\
✔ Checked multicollinearity before final model

------------------------------------------------------------------------

## 📈 Descriptive Insights

### 💰 Price Distribution

-   **Average Price:** \~\$540K\
-   **Std. Deviation:** \~\$367K\
-   **Range:** \~\$7.6M\
-   Strong right-skew → luxury outliers drive tail

### 📏 Property Size

-   Avg living area: \~2,080 sqft\
-   Significant variation in lot sizes\
-   Wide diversity in housing inventory

------------------------------------------------------------------------

## 🤖 Regression Model Performance

After iterative model refinement:

-   **R² = 0.6793**
-   Model explains \~68% of price variability
-   All retained predictors statistically significant (p \< 0.05)

### 📌 Strongest Positive Price Drivers:

-   Living area (sqft_living)
-   Bathrooms
-   Waterfront properties
-   View & Condition
-   Higher Latitude (location premium)
-   Larger neighboring homes (sqft_living15)

### 📉 Negative Relationships:

-   Year sold (2014 slightly lower than 2015)
-   Longitude
-   Bedrooms (possible structural multicollinearity effect)

------------------------------------------------------------------------

## 🧪 Hypothesis Testing

### 1️⃣ Waterfront Premium

✔ Supported\
Waterfront homes are priced over **\$1M higher on average**.

### 2️⃣ Older Houses Lower Price

✔ Supported\
Each additional year reduces the price by \~\$674.\
However, age alone has weak explanatory power (R² ≈ 0.003).

------------------------------------------------------------------------

## 📉 Model Diagnostics

-   Residual plots show no clear pattern
-   No major heteroscedasticity concerns
-   Model assumptions reasonably satisfied

------------------------------------------------------------------------

## 💡 Key Business Takeaways

-   Location and structural square footage are dominant price drivers.
-   Waterfront and quality features generate a substantial premium.
-   The market appreciated between 2014 and 2015.
-   Renovations significantly improve valuation.
-   Neighborhood effect matters --- surrounding property size impacts
    pricing.

------------------------------------------------------------------------

## 🛠 Tools & Skills Demonstrated

-   Microsoft Excel (Advanced Regression)
-   Statistical Modeling
-   Correlation Analysis
-   Residual Diagnostics
-   Business Interpretation of Statistical Output
-   Hypothesis Testing

------------------------------------------------------------------------

## 📂 Repository Structure

    ├── README.md
    ├── Business_Analytics_Final_Project_Submission.pdf
    ├── Dataset.xlsx
    ├── Regression_Output.xlsx
    └── Visualizations/

------------------------------------------------------------------------

## 📌 Why This Project Matters

This project demonstrates the ability to:

-   Translate raw real-world data into actionable insights\
-   Build statistically sound predictive models\
-   Interpret coefficients in a business context\
-   Connect analytics output to decision-making

------------------------------------------------------------------------

📎 Full detailed report available in the project PDF.

------------------------------------------------------------------------

© 2024 Mrinal Mishra

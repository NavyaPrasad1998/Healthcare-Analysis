# Healthcare-Analysis
Cost and Care: Analyzing Billing Amounts and Length of Stay in Healthcare


## **Project Overview**
This project investigates the relationships between patient demographics, medical conditions, admission types, length of stay, and hospital billing amounts. By leveraging statistical methods and data visualization, the study aims to uncover patterns and insights that could help optimize healthcare costs without compromising the quality of care.

## **Objectives**
1. Analyze how **length of stay** impacts **hospital billing amounts**.
2. Investigate factors such as **age, gender, medical condition**, and **admission type** to determine their influence on billing and length of stay.
3. Provide actionable insights using statistical models and visualizations to improve healthcare efficiency.

---

## **Dataset**
The dataset contains synthetic healthcare data with 10,000 patient records, including the following attributes:
- **Demographics:** Age, Gender
- **Medical Information:** Medical Condition, Admission Type, Length of Stay
- **Financials:** Billing Amount
- **Categorical Information:** Insurance Provider, Admission and Discharge Dates

Data Source: [Kaggle Healthcare Dataset](https://www.kaggle.com) (synthetic and experimental).

---

## **Methodology**
1. **Data Preparation:**
   - Cleaned and preprocessed the dataset.
   - Created a new variable `Length of Stay` calculated from admission and discharge dates.
   - Converted categorical variables to factors for statistical analysis.

2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics for variables like age, billing amounts, and length of stay.
   - Visualized data using histograms, box plots, and scatter plots.

3. **Statistical Analysis:**
   - **Hypothesis Testing:** Applied T-tests and ANOVA to analyze differences in billing amounts and length of stay across groups.
   - **Regression Modeling:** Built Generalized Linear Models (GLMs) to predict billing amounts and identify key influencing factors.
   - **Model Diagnostics:** Validated assumptions using residual plots, Q-Q plots, and leverage analysis.

4. **Key Analytical Methods:**
   - Tukey’s Post Hoc Test: Identified specific group differences post-ANOVA.
   - Confidence Intervals: Analyzed mean length of stay across medical conditions.
   - Stepwise Model Selection: Optimized predictive models using AIC-based backward and forward elimination.

---

## **Key Findings**
1. **Admission Type Impact on Billing Amounts:**
   - Emergency admissions significantly increased billing amounts compared to elective admissions.
   - ANOVA and Tukey’s test confirmed these differences.

2. **Length of Stay and Billing Amounts:**
   - Regression analysis showed no significant linear relationship between length of stay and billing amounts.

3. **Medical Condition and Costs:**
   - No statistically significant difference in billing amounts across various medical conditions.
   - Length of stay was uniform across conditions, with a mean of ~15.5 days.

4. **Demographics Impact:**
   - Age and gender did not significantly influence billing amounts.

---

## **Visualizations**
1. **Distribution of Length of Stay:** Histogram showing the majority of hospital stays ranged from 8 to 23 days.
2. **Billing Amount by Admission Type:** Box plots highlighting significant cost variations.
3. **Regression Diagnostics:** Residual and Q-Q plots to validate model assumptions.

---

## **Technologies Used**
- **Programming Language:** R
- **Libraries:** `dplyr`, `ggplot2`, `MASS`, `lubridate`
- **Statistical Methods:** ANOVA, T-tests, Generalized Linear Models (GLMs)

---

## **Future Scope**
1. Explore **machine learning models** for predicting healthcare costs and length of stay.
2. Incorporate additional variables like **socio-economic factors** and **regional data** for deeper analysis.
3. Conduct longitudinal studies to evaluate the impact of healthcare policies on billing and patient outcomes.

---

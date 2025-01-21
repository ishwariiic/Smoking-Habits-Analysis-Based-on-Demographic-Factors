# Smoking-Habits-Analysis-Based-on-Demographic-Factors
Smoking Habits Analysis Based on Demographic  Factors-Performing Chi-Square Test on Dataset using Python-—This project focuses on an in-depth analysis of smoking
 behaviors with a focus on understanding the association between
 smoking habits and gender. The primary objective is to assess if
 smoking behavior is influenced by gender and other demographic
 factors such as age, income, and education level. This study
 includes a statistical hypothesis test, exploratory data analysis,
 feature reduction through Principal Component Analysis (PCA),
 and classification modeling. The findings provide insights into the
 demographic factors influencing smoking behaviors and highlight
 significant predictors for potential health interventions. 
 
 B. Chi-square Test- Statistical Analysis
 . Statistical Analysis,
 • Chi-Square Test for Independence:
 • Purpose: To determine if there is a significant association
 between gender and smoking status.
 • Hypothesis Setup:
 • Null Hypothesis (H0): Smoking behavior is independent
 of gender.
 • Alternative Hypothesis (H1): Smoking behavior is not
 independent of gender.
 • Test Execution:
 • Calculate the Chi-Square statistic by cross-tabulating gen
der and smoking status.
 • Calculate the degrees of freedom and obtain the p-value.
 • Display results and visualize the Chi-Square distribution
 if possible.
 • Conclusion:
 • Based on the p-value, conclude if gender significantly
 affects smoking behavior.
 • Interpretation of whether smoking behavior varies mean
ingfully across genders

 
  **INTRODUCTION**

  
 **Background**: Smoking is a global public health concern
 with well-documented risks. Demographic factors can influ
ence smoking habits, with previous studies suggesting cor
relations between smoking and factors such as gender, age,
 income, and education.
 
 **Objective**: This project aims to evaluate the relationship
 between smoking behavior and demographic characteristics,
 specifically analyzing the dependence of smoking habits on
 gender. We will employ statistical testing and data analysis
 to assess these relationships and build a predictive model to
 classify smoking behavior.
 
**Significance** Insights from this study can help in creating
 targeted anti-smoking campaigns and healthcare initiatives by
 identifying demographic groups more prone to smoking.
 
**What Is a Chi-Square Test?**

 The Chi-Square test is a statistical procedure for determin
ing the difference between observed and expected data. This
 test can also be used to determine whether it correlates to the
 categorical variables in our data. It helps to find out whether a
 difference between two categorical variables is due to chance
 or a relationship between them. In this test:
 
1]Variance is double the times the number of degrees of
 freedom.
 
 2]Mean distribution is equal to the number of degrees of
 freedom.
 
 3]When the degree of freedom increases, the Chi-Square
 distribution curve becomes normal

**II. DATA ANALYTICS EVALUATION**
*A. Dataset Overview*
**Data Source:** The dataset is sourced from Kaggle’s Smoking
 Habits dataset.
 
 *Feature Description:*
 
 • Gender: Categorical variable (Male, Female).
 
  • Age: Continuous variable representing the age of partic
ipants.

 • Income Level: Ordinal variable indicating income brack
ets.

 • Education Level: Categorical or ordinal variable repre
senting educational attainment.

 • Smoking Status: Binary variable (smoker or non
smoker).

**Data Preprocessing:**

 • *Handling Missing Values*: Outline techniques used, such
 as mean imputation for age or mode imputation for
 categorical features.
 
 • *Encoding*: Convert categorical variables (gender, education) into numeric form using one-hot or label encoding.

 • *Normalization*: Scale continuous variables to ensure com
parability across features.

 **What Are Categorical Variables?**
 
 Categorical variables belong to a subset of variables that can
 be divided into discrete categories. Names or labels are the
 most common categories. These variables are also known as
 qualitative variables because they depict the variable’s quality
 or characteristics.
 
 Categorical variables can be divided into two categories:
 
 **Nominal Variable:** A nominal variable’s categories have
 no natural ordering. Example: Gender, Blood groups.
 
 **Ordinal Variable:** A variable that allows the categories to be sorted
 is ordinal variables. Customer satisfaction (Excellent, Very
 Good, Good, Average, Bad, and so on) is an example.
 
 **A. Exploratory Data Analysis (EDA)**
 Descriptive Statistics: Present detailed descriptive statis
tics:

 • *Mean and Median:* To understand the central tendency of
 continuous variables like age and income.
 
 • *Variance*: To assess the spread or variability within each
 feature.
 
 • *Skewness:*Measure the asymmetry of the distribution (to
 detect any skewed patterns).
 
 •*Kurtosis:* To assess the ”tailedness” of the distribution (to
 identify any outliers or extreme values).
 
 • *Correlation Analysis:* Generate a correlation matrix and heatmap for continuous
 features to visualize relationships.
 
 • *Discussion* on any notable correlations, e.g., if age corre
lates with income or if education level influences income.

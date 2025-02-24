# Thyroid-Cancer-Risk-Research
Analyzing Thyroid Cancer Risk Among Patient


## Problem Statement:

The dataset provides clinicopathologic features of patients diagnosed with well-differentiated thyroid cancer. These features, such as age, gender, ethnicity, family history, radiation exposure, iodine deficiency, smoking, obesity, diabetes, and various thyroid-related lab results, are critical in determining the recurrence risk of thyroid cancer. The objective is to analyze these features and maybe build a predictive model that can estimate the risk of recurrence of thyroid cancer in these patients based on the given attributes.

### Objectives:

Data Preprocessing: Clean the data by handling missing values, outliers, and transforming variables where needed (e.g., categorical to numeric, creating age bins).

Exploratory Data Analysis (EDA): Explore the relationships between clinicopathologic features and thyroid cancer recurrence risk.

Correlation Analysis: Identify which variables are strongly correlated with recurrence risk, and if some features might not contribute much to prediction.


#### Research Questions:
What is the distribution of recurrence risk across the dataset?

How do different clinicopathologic factors (e.g., age, TSH level, smoking, etc.) correlate with the recurrence of thyroid cancer?

Are there specific features or combinations of features that significantly affect the recurrence risk?

What is the impact of lifestyle factors (smoking, obesity, etc.) on recurrence?

Does family history of thyroid cancer or radiation exposure increase the risk of recurrence?

What is the relationship between thyroid hormone levels (TSH, T3, T4) and recurrence risk?

How well can we predict thyroid cancer recurrence using the given features?

Are there any gender, ethnicity, or age-related trends in recurrence risk?






## Findings


1. Statistical Analysis:
Age Range: The age of patients in the dataset ranges from 15 to 89 years, with the minimum age being 15 and the maximum age being 89.
Nodule Size: The size of thyroid nodules varies from 0 to 5.0 mm, with the largest size being 5.0 mm and the smallest size being 0 mm.

3. Distribution of Thyroid Cancer Risk:
From the dataset, it is observed that most patients have a low risk of thyroid cancer. Only a few patients are categorized under high risk for the cancer.


5. Relationship Between Numerical Features:
The correlations between numerical features (Age, TSH Level, T3 Level, T4 Level, Nodule Size) and Thyroid Cancer Risk are generally very weak.
The majority of the correlations between numerical variables are close to 0, suggesting that there are little to no linear relationships between these variables.


7. Distribution of Key Numerical Features:
Age Distribution: The dataset includes patients from various age groups, with ages ranging from 18 to 89 years.


TSH Level: The distribution shows that most patients have a TSH level between 0 and 6.0.

Nodule Size: The majority of patients have a nodule size within the 3-5 mm range.


9. Distribution of Categorical Variables:
Gender: Visuals indicate that females tend to have higher recurrence risks for thyroid cancer compared to males. Additionally, females have a higher proportion of low recurrence risk.

Smoking: Non-smokers tend to have a higher recurrence risk compared to those who smoke.

Obesity: Non-obese patients have a higher recurrence risk than obese individuals.

Family History: Patients who have a family history of thyroid cancer show a higher risk of developing thyroid cancer.

11. Analyzing the Impact of Age and Gender on Recurrence:
Age: From the analysis, patients in the 18-30 age group have a higher thyroid cancer risk compared to other age groups. The 30-39 age group follows as the second highest risk group for thyroid cancer.

13. Correlation Between Lifestyle Factors (Smoking, Obesity, etc.) and Recurrence:
Lifestyle Factors such as smoking and obesity seem to play a role in the recurrence risk for thyroid cancer, with non-smokers and non-obese individuals showing higher recurrence risk.


15. Effect of Radiation Exposure on Recurrence Risk:
Radiation exposure is inversely correlated with recurrence risk, as patients with little or no radiation exposure have a higher recurrence risk compared to those who have been exposed to radiation.


## Conclusion:

Age and Gender: Gender appears to influence recurrence risk, with females showing a higher recurrence rate, while younger patients (18-30 years) also exhibit a higher risk. This suggests that age and gender are potential factors to monitor when assessing thyroid cancer risk.

Numerical Features: The correlation between numerical features like Age, TSH Level, and Nodule Size with Thyroid Cancer Risk is weak, indicating that these features alone might not be strong predictors of recurrence.

Lifestyle Factors: Lifestyle factors such as smoking, obesity, and family history show notable relationships with recurrence risk. Non-smokers and non-obese patients show higher risk, highlighting the potential role of lifestyle in the disease’s progression.

Radiation Exposure: Patients who have no or limited radiation exposure have a higher recurrence risk, suggesting that radiation exposure may be protective or that these patients are under different treatment protocols.


## Recommendations:
Further Analysis of Risk Factors:

Since age, gender, and family history show some correlation with thyroid cancer recurrence, these variables should be considered in further predictive models.

Additional data such as lifestyle factors (diet, exercise) and genetic markers should be incorporated to improve the model's predictive accuracy.

Targeted Monitoring:

Focus on young adults (18-30 years) and females, as they show a higher risk for thyroid cancer recurrence. Monitoring these groups more closely could potentially improve early detection and intervention.

Promote Healthy Lifestyles:

Given the relationship between smoking, obesity, and higher recurrence risk, there should be efforts to educate patients about lifestyle modifications (e.g., smoking, weight management) that may help reduce recurrence risks.

Radiation Exposure:
While radiation exposure is inversely correlated with recurrence risk, it’s essential to evaluate the long-term effects of radiation treatment and explore alternative therapies for those with no radiation exposure.

Use of More Sophisticated Models:

Given the weak correlations observed between the numerical features and thyroid cancer risk, advanced statistical techniques such as machine learning models (e.g., logistic regression, decision trees) should be considered to uncover more complex patterns in the data.
Clinical Application:

Physicians and healthcare providers should take into account not only the clinical and biological factors but also lifestyle choices and family history when assessing the recurrence risk of thyroid cancer in patients.







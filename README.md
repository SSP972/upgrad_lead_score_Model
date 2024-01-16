# Lead_score_Model

## Introduction
This GitHub repository contains the analysis and modeling work done for X Education. The objective is to assist the company in selecting the most promising leads, those most likely to convert into paying customers. The analysis is based on data provided by X Education, which includes information about potential customer visits, time spent on the site, sources of leads, conversion rates, and more.

## Background
X Education is an online education company catering to industry professionals. The company markets its courses on various websites and search engines. Leads are generated through website visits, form submissions, video views, and past referrals. The sales team engages with these leads to convert them into paying customers, with a typical lead conversion rate of around 30%.

## Objectives
1. Identify the most promising leads.
2. Build a model to identify hot leads.
3. Deploy the model for future use.

## Analysis Steps
1. **Cleaning Data:**
   - Addressed null values and replaced irrelevant options with null values.

2. **Exploratory Data Analysis (EDA):**
   - Checked data conditions.
   - Identified irrelevant elements in categorical variables.
   - Recognized potential outliers, particularly in the "No Conversion" class.

3. **Train-Test Split:**
   - Split the dataset into training and testing sets (75% and 25%, respectively).

4. **Model Building:**
   - Evaluated Random Forest, Gradient Boosting, LightGBM, and Catboost models.
   - Tested various metrics to choose the best model for analysis.

5. **Model Evaluation:**
   - Utilized confusion matrix and ROC curve for optimal cutoff value.
   - Analyzed accuracy, sensitivity, and specificity (approximately 80%).

6. **Tune Hyperparameters:**
   - Recommended further optimization and hyperparameter tuning, especially for Random Forest and CatBoost models.

7. **Prediction:**
   - Achieved accuracy, sensitivity, and specificity of ~90% on test data.

8. **Precision – Recall:**
   - Used Precision-Recall method to determine precision (~91.8%) and recall (~86.4%).

## Conclusion
The analysis highlighted key variables influencing potential buyers, such as total time spent on the website, total number of visits, lead source, last activity, lead origin, and current occupation. By focusing on these factors, X Education can significantly improve its lead conversion rates. Further optimization and hyperparameter tuning are recommended for enhanced results. The repository provides detailed insights into the analysis process and model evaluation.

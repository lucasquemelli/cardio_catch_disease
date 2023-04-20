# Cardio Catch Disease

<code><img width="100%" src="https://github.com/lucasquemelli/cardio_catch_disease/blob/main/Images/cardio_catch.jpeg"></code>

# 1. Business Problem

**Description**

--- 

**Cadio Catch Disease** is a company whose business model is detecting heart disease in the early stages.The company offers an early diagnosis of cardiovascular disease for a certain price. Currently, the diagosis is has been made manually. The current accuracy is between 55% and 60%, because of the complex diagnosis and the team's fatigue. We must know:

1. Each diagnosis costs about $1000,00.
2. The price will vary according to the precision: the customer pays $500.00 for every 5% accuracy above 50%.
3. If the diagnostic precision is 50% or below, the customer doesn't pay for it.

**Purpose**

---

We must incease the diagnosis precision and make it more stable. To do it, we built a classification model to predict the cardiovascular diseases. 

**Business Questions**

--- 

1. What are the accuracy and the precision of the model? 
2. How much profit will Cardio Catch Disease have after the project? 
3. How reliable is our result?

# 2. Business Assumptions (Formulated Hypotheses)

The following hypotheses (or questions) were formulated in order to be tested/answered:

**H1.** There are less cases of heart diseases among young people (up to 30s).

**H2.** The cases of heart diseases does not significantly depend on the height.

**H3.** The higher the weight, the higher is the cases of heart diseases.

**H4.** The cases of heart diseases does not significantly depend on the gender.

**H5.** There are more cases of heart diseases for people presenting well above normal levels of cholesterol.

**H6.** There are more cases of heart diseases for people presenting well above normal levels of glucose.

**H7.** The are more cases of heart diseases for people who smokes than for people who does not.

**H8.** The are more cases of heart diseases for people who intakes alcohol than for people who does not.

**H9.** The are more cases of heart diseases for people who does not do any physical activity than for people who does.

**H10.** How are the cases of heart diseases distributed among systolic blood pressures?

**H11.** How are the cases of heart diseases distributed among diastolic blood pressures?

# 3. Solution Strategy

**Step 01 - Data Description:** cleaning data, changing data type, treating missing values, check balance of data, and descriptive statistics.

**Step 02 - Feature Engineering:** creating new features that may better explain the phenomenon.

**Step 03 - Feature Filtering and Selection:** rows filtering and columns selection.

**Step 04 - Exploratory Data Analysis (EDA):** univariate analysis, bivariate analysis (hypotheses test) and multivariate analysis.

**Step 05 - Data Preprocessing:** rescaling, encoding and transformation.

**Step 06 - Feature Selection:** removing high correlated features and using Boruta algorihtm with Random Forest Regressor to select the most relevant features.

**Step 07 - Machine Learning Modelling:** testing and comparing Machine Learning models.

**Step 08 - Hyperparameter Fine Tuning:** determining the parameters which maximize the model learning.

**Step 09 - Business Performance:** translating the results into business.

# 4. Top 4 Data Insights

**H2.** The cases of heart diseases does not significantly depend on the height.

**FALSE.** Smallers people are more prone to have heart diseases.

**H4.** The cases of heart diseases does not significantly depend on the gender.

**FALSE.** We have higher volume of female with heart disease. Additionally, female people are more prone to have heart disease.

**H7.** The are more cases of heart diseases for people who smokes than for people who do not.

**FALSE.** There are much more cases for people who do not smoke. Additionally, people who do not smoke are slightly more prone to have heart disease.

**H8.** The are more cases of heart diseases for people who intakes alcohol than for people who do not.

**FALSE.** There are more cases for people who do not intake alcohol. Additionally, they are slightly more prone to have heart disease.

# 5. Business Results

Random Forest Classifier predicts propensity to heart disease with 72.16 % of average precision. It results in a minimum of USD 2000,00 of profit, which is better than USD 1500,00 as the maximum profit for the current diagnosis.

# 6. Conclusions

By using a Machine Learning model to predict heart diseases, we would improve the minimum revenue from 0 to 2000 dollars for every diagnosis.

# 7. Next Steps

Understanding why LGBM Classifier could not work and try to train this model in order to improve the precision. 

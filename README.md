## **Classification:**

In machine learning, classification refers to a predictive modelling problem
where the target variable is categorical in nature in the form of Yes/No, 0s/1s
.

**Dataset used :** [Pima Indians Diabetes Database \|
Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

**Description:**

NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases)
research creates knowledge about and treatments for the most chronic, costly,
and consequential diseases.

The dataset used in this project is originally from NIDDK. The objective is to
predict whether or not a patient has diabetes, based on certain diagnostic
measurements included in the dataset.

**Problem Statement:**

Build a model to accurately predict whether the patients in the dataset have
diabetes or not.

Dataset Description

The datasets consists of several medical predictor variables and one target
variable (Outcome). Predictor variables includes the number of pregnancies the
patient has had, their BMI, insulin level, age, and more.

| **Variables**            | **Description**                                                               |
|--------------------------|-------------------------------------------------------------------------------|
| Pregnancies              | Number of times pregnant                                                      |
| Glucose                  | Plasma glucose concentration in an oral glucose tolerance test                |
| BloodPressure            | Diastolic blood pressure (mm Hg)                                              |
| SkinThickness            | Triceps skinfold thickness (mm)                                               |
| Insulin                  | Two hour serum insulin                                                        |
| BMI                      | Body Mass Index                                                               |
| DiabetesPedigreeFunction | A function which scores likelihood of diabetes based on family history        |
| Age                      | Age in years                                                                  |
| Outcome                  | Class variable (either 0 or 1). 268 of 768 values are 1, and the others are 0 |

###
**Task Performed**

**Data Exploration - Part 1:**

1\. Performed descriptive analysis. On the columns below, a value of zero does not make sense and thus indicates missing value:  

  ??? Glucose  
  ??? BloodPressure  
  ??? SkinThickness  
  ??? Insulin  
  ??? BMI  

2\. Visually exploring these variables using histograms and treating the missing values accordingly.  
3\. There are integer and float data type variables in this dataset. Creating a count (frequency) plot describing the data types and the count of variables.

**Data Exploration - Part 2:**

1\. Checking the balance of the data by plotting the count of outcomes by their value.  
2\. Creating scatter charts between the pair of variables to understand the relationships.  
3\. Performing correlation analysis. Visually exploring it using a heat map.

**Data Modeling:**

1\. Applying different classification algorithm to build a model.  
2\. Creating a classification report by analyzing sensitivity, specificity, AUC(ROC curve) for each model.  
3\. Comparing various model results to find the best performing model.

**Data Reporting:**

Diabetes Report

![Dashboard](https://user-images.githubusercontent.com/69600920/216275096-4ea9a3fd-acd5-41fe-9993-6eed31a85f0d.png)

Tableau Dashboard: https://public.tableau.com/views/Capstone2_1_16141863764220/DiabetesReport?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

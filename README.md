### Introduction 
Heart failure is a chronic condition in which the heart's ability to pump blood is inadequate to meet the body's needs. It is a major public health concern, affecting millions of people worldwide and leading to significant morbidity and mortality. Early prediction and effective management of heart failure can greatly improve patient outcomes and reduce healthcare costs. In this project, we aim to build a classification model to predict the occurrence of a death event (DEATH_EVENT) in patients with heart failure using clinical and laboratory data.

The dataset used in this project, obtained from the UCI Machine Learning Repository, consists of 299 patient records and includes 13 features such as age, anemia, creatinine phosphokinase, diabetes, ejection fraction, high blood pressure, platelets, serum creatinine, serum sodium, sex, smoking, time, and the target variable DEATH_EVENT. This dataset provides a comprehensive set of predictors that can be used to develop a robust predictive model.
### Dataset 
This dataset contains the medical records of 299 patients who had heart failure, collected during their follow-up period, where each patient profile has these 13 clinical features.
      age: Age of the patient [Integer] 

      anaemia: Decrease of red blood cells or hemoglobin [Binary] 

      creatinine_phosphokinase: Level of the CPK enzyme in the blood [Integer] 

      diabetes: If the patient has diabetes [Binary] 

      ejection_fraction: Percentage of blood leaving the heart at each contraction [Integer] 

      high_blood_pressure: If the patient has hypertension [Binary] 

      platelets: Platelets in the blood [Continuous] 

      serum_creatinine: Level of serum creatinine in the blood [Continuous] 

      serum_sodium: Level of serum sodium in the blood [Integer] 

      sex: Sex of the patient [Binary]

      smoking: if the patient smokes or not [Binary]

      time: follow-up period [Integer]

      death_event: if the patient died during the follow-up period [Binary] 

The target variable in the dataset is death_event. Rest all are features.
### Project Contents
  This repository includes:
  
    Jupyter Notebook with code covering the following areas of modeling
    
      Introduction
      Exploratory Data Analysis
      Logistic Regression
      Model Interpretation
      Conclusion and Recommendations.
    
### Dependencies
    To run the code and experiments in this project, you'll need the following libraries and dependencies:

      python (version 3.X)
      pandas
      matplotlib.pyplot
      seaborn
      sklearn

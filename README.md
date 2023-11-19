# ocd-patient-dataset
Dataset Description: OCD Patient Data for Machine Learning Analysis

Overview

This dataset comprises anonymized records of patients diagnosed with Obsessive-Compulsive Disorder (OCD). It is structured to facilitate analysis and modeling related to OCD diagnosis, symptomatology, treatment, and comorbid conditions.
Some of the key features are:
1.	Patient Demographics

•	Data Points: Age, Gender, Ethnicity, Marital Status, Education Level.
•	Purpose: Provides a basic understanding of the patient's background, essential for demographic analysis and correlation studies.
2.	OCD-Specific Information

•	Data Points: OCD Diagnosis Date, Duration of Symptoms (in months), Family History of OCD.
•	Purpose: Offers insight into the onset and familial patterns of OCD, which are crucial for diagnosis prediction models.
3.	Clinical Assessment

•	Data Points: Yale-Brown Obsessive Compulsive Scale (Y-BOCS) Scores for Obsessions and Compulsions.
•	Purpose: Quantifies the severity of OCD symptoms, vital for symptom analysis and severity prediction models.
4.	Medical and Psychological History

•	Data Points: Previous Diagnoses, Depression Diagnosis, Anxiety Diagnosis.
•	Purpose: Helps in understanding the patient's overall mental health profile, instrumental for comorbidity identification models.
5.	Symptom Details

•	Data Points: Type of Obsession (e.g., harm-related, contamination), Type of Compulsion (e.g., checking, washing).
•	Purpose: Facilitates a detailed analysis of OCD symptom patterns, aiding in tailored treatment approaches.
6.	Treatment Information

•	Data Points: Medications prescribed (e.g., SNRI, SSRI, Benzodiazepine).
•	Purpose: Enables the study of treatment efficacy and patterns in medication prescriptions.
Project Summary: Classification Models for OCD Diagnosis and Comorbidity Identification

Objective

This project focuses on developing machine learning classification models to enhance the diagnostic process and identification of comorbidities in patients potentially suffering from Obsessive-Compulsive Disorder (OCD).
Key Components
1.	Diagnosis Prediction Model
•	Purpose: To predict the likelihood of a new patient having OCD based on available data.
•	Data Utilized: Demographic information (age, gender, ethnicity), previous medical and psychological diagnoses, family history of OCD, and descriptions of initial symptoms.
•	Approach: Implement classification algorithms like Logistic Regression, Decision Trees, or Support Vector Machines to differentiate between OCD and non-OCD cases. Feature engineering will play a crucial role in enhancing model performance.
2.	Comorbidity Identification Model

•	Purpose: To assess the likelihood of comorbid conditions, particularly depression and anxiety, in patients with OCD symptoms.
•	Data Utilized: OCD symptom details, patient demographics, and any existing psychological evaluations.
•	Approach: Use classification techniques to identify patterns linking OCD symptoms to comorbid conditions. Models such as Random Forests or Gradient Boosting could be effective in handling the complexities of comorbidities.

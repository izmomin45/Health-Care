## Healthcare Dataset Analysis

Project Overview

This project involves analyzing a healthcare dataset that includes patient information related to age, gender, medical conditions, and treatment details. The primary goal is to create meaningful insights into patient demographics, hospital performance, billing amounts, insurance payments, and recovery times. The dataset has been processed and visualized using Excel, with a focus on generating an easy-to-understand dashboard for further decision-making and reporting.

Dataset Description
The dataset contains 55500 patient records, each describing various attributes of a hospital stay and treatment. Below is a description of the key columns:

Age: The age of the patient.
Age Group: Categorized into four groups: Young, Teenage, Middle Age, and Old.
Gender: Male or Female.
Blood Type: Blood group of the patient (A+, B-, O+, etc.).
Medical Condition: The primary illness or disease (Cancer, Diabetes, Obesity, etc.).
Date of Admission: The date when the patient was admitted to the hospital.
Month of Admission: The month in which the patient was admitted.
Doctor: The doctor attending to the patient.
Hospital: The name of the hospital where the patient was treated.
Insurance Provider: The company covering the patient's medical expenses.
Billing Amount: The total cost billed to the patient’s insurance company.
Room Number: The patient’s room number during their stay.
Admission Type: The type of admission (Elective, Emergency, Urgent).
Discharge Date: The date the patient was discharged from the hospital.
Days to Recover: The number of days the patient stayed in the hospital.
Medication: The primary medication prescribed during treatment.
Test Results: Results of the medical tests conducted (Normal, Abnormal, Inconclusive).

 # Analysis Goals
The analysis primarily aims to extract insights from the dataset regarding:

Average recovery time for various medical conditions.
Patient distribution by age group and gender.
Admission types and their frequency across patient groups.
Billing trends for hospitals and insurance providers.
Insurance coverage comparison across various medical conditions and hospitals.
Doctor performance and patient recovery times.
Seasonal trends by examining patient admissions across months.
Data Insights
Some key insights from the analysis:

Average Recovery Time: The overall average recovery time is 15.48 days. Patients with cancer have the longest recovery time, while those with hypertension and diabetes recover relatively faster.
Patient Age Distribution: The dataset reveals that the old age group (51.6%) forms the largest proportion of patients, with the young group accounting for about 23%.
Admission Types: Admissions are equally distributed between Elective, Emergency, and Urgent, each comprising around one-third of the total admissions.
Hospital Billing: Smith Ltd has the highest billing, totaling over $832,000, while Inc Brown follows with over $512,000.
Insurance Providers: Cigna has billed the highest amount at $144.6 million, with Medicare and Blue Cross also covering significant portions of total patient costs.
Doctors and Recovery: The dataset highlights variations in patient recovery times depending on the doctor, with recovery ranging from 2 days to over 30 days depending on the medical condition and treatment.
Seasonal Trends: Admissions are fairly consistent across months, with August and September seeing higher patient intakes compared to other months.
Visualizations & Dashboard
A key part of the project was building an Excel Dashboard to visualize the insights extracted from the data. Key charts include:

Disease-wise Average Recovering Days: A bar chart displaying the average recovery time for each disease.
Percentage of Patients by Age Group: A donut chart showing the breakdown of patients by their age category.
Admission Type Distribution: A pie chart illustrating the proportion of elective, urgent, and emergency admissions.
Hospital Billing Amounts: A horizontal bar chart comparing billing amounts across different hospitals.
Insurance Company Billing: A line graph summarizing the total billed amount across different insurance companies.
Future Work
This dataset offers opportunities for further exploration. Potential future analyses may include:

Predictive modeling to estimate recovery times based on patient attributes.
Cluster analysis to find patterns in patient demographics and treatment outcomes.
Deeper financial analysis of hospital and insurance company interactions.
How to Use the Dashboard
Download the Excel File: The dashboard has been created in an Excel file available on GitHub.
Interact with Filters: Gender and month filters are included to dynamically update charts based on user input.
View Key Metrics: At the top, important summary statistics such as the number of doctors, hospitals, average days to recover, and recovery rate are displayed.
Conclusion
This analysis presents valuable insights into the healthcare system, offering a comprehensive look at patient demographics, recovery rates, and financial billing. The dashboard allows for easy interpretation and interaction with the data, making it a useful tool for healthcare professionals, insurers, and hospital administrators.



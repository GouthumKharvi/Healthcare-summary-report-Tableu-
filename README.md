# Healthcare-summary-report-Tableu-
This project analyzes patient health metrics from a Healthcare dataset, focusing on diabetes, blood pressure, and BMI. Two interactive dashboards highlight diabetic and non-diabetic distributions and summarize patient data by blood pressure and BMI, culminating in a comprehensive story of key insights and visualizations.




https://github.com/user-attachments/assets/b5ba55c0-8a58-48d6-9ae4-bde5e955d6b8



# Healthcare Analytics Dashboard

## Project Overview
This project focuses on analyzing health metrics from a dataset that includes information about patients' blood pressure, BMI, glucose, insulin levels, and diabetes status for individuals aged 20 and above. Using Tableau, two interactive dashboards have been created to visualize key insights, followed by a comprehensive story that summarizes the findings.

## Project Objectives
- **Visualize the distribution of diabetic and non-diabetic patients.**
- **Summarize patient health data by blood pressure and BMI categories.**
- **Provide insights through interactive dashboards and a narrative story.**

## Tools Used
- **Data Analysis:** Tableau (Public/Desktop)
- **Data Source:** Healthcare.xls (CSV format)

## Data Description
The dataset contains the following fields:
- **Blood Pressure**
- **BMI (Body Mass Index)**
- **Glucose Levels**
- **Insulin Levels**
- **Diabetes Outcome (1 = Diabetic, 0 = Non-diabetic)**

## Dashboards

### Dashboard 1: Diabetic vs. Non-Diabetic Distribution
- **Visual Elements:**
  - An image related to healthcare.
  - Text object providing a meaningful title.
- **Analysis Focus:** Visual representation of the distribution of diabetic and non-diabetic patients.

### Dashboard 2: Patient Health Summary
This dashboard includes multiple views:

#### View 1: Diabetic/Non-Diabetic Distribution
- **Visualization Type:** Shapes
- **Calculated Field:** Classifies patients based on the “Outcome” field (1 for Diabetic, 0 for Non-diabetic).
- **Features:**
  - Percent distribution of diabetic vs. non-diabetic patients.
  - Tooltips displaying patient counts.
  - Action filters enabled.

#### View 2: Patient Summary by Blood Pressure
- **Visualization Type:** Shapes
- **Features:**
  - Displays patient count and blood pressure categories on labels.
  - Differentiates diabetic and non-diabetic patients using color coding.
  - Action filters enabled.

#### View 3: Histogram of BMI by Age Groups
- **Visualization Type:** Histogram
- **Details:**
  - Age bins created in increments of 5 (e.g., 20-24, 25-29).
  - Average BMI displayed on top of each bar, rounded to two decimals.
  - Color palette using shades of red based on average BMI.

#### View 4: Patient Distribution by BMI Type
- **Visualization Type:** Single Bar Chart
- **Calculated Field:** Classifies patients by BMI type:
  - Underweight: BMI < 18.5
  - Healthy Weight: 18.5 ≤ BMI < 25
  - Overweight: 25 ≤ BMI < 30
  - Obese: BMI ≥ 30
- **Features:**
  - Action filters enabled.

#### View 5: Patient Breakdown by Blood Pressure and Diabetes
- **Visualization Type:** Bar Chart
- **Details:** Highlights diabetic patients with high and low blood pressure.

#### View 6: Heat Map of Health Factors by Age Group
- **Visualization Type:** Heat Map
- **Features:** Displays various health factors categorized by age group.

## Story: Healthcare Summary Report
- **Story Name:** Healthcare
- **Story Title:** Healthcare Summary Report
- **Description:** A summary of key insights from the analysis.
- **Story Points:**
  1. Dashboard 1: Diabetic vs. Non-Diabetic Distribution
  2. Dashboard 2: Patient Health Summary
  3. Heat Map Worksheet

## Conclusion
This project aims to provide valuable insights into the health metrics of patients, enabling healthcare professionals to make data-driven decisions. Through interactive visualizations, we can better understand the relationships between diabetes, blood pressure, and BMI, ultimately improving patient care.

# Student Demographics Analysis Using Power BI

## Overview

This project explores the demographics of students that applied to the **Tech Moms** program using application data. The dataset provides insights into the employment status, education levels, household income, and diversity of the applicants. Using Power BI, I visualized key trends such as employment categories, income distribution, and the representation of various racial and ethnic groups. The goal is to understand the applicant/student profile and support program decision-making for future cohorts.

## Project Details

### 1. Dataset

The dataset consists of various fields including:
- **Applicant Status**: Tracks the application status (e.g., "Assigned Cohort", "Declined Attending").
- **Employment Status**: Includes categories such as "Full-Time", "Part-Time", and "Unemployed."
- **Education Level**: Ranges from "Some College" to "Bachelor's or Above."
- **Household Income**: Shows the income brackets for each applicant's household.
- **Race/Ethnicity**: Identifies the racial or ethnic group of the applicants.
- **Create Date**: The date when the application was submitted.

### 2. Data Preparation in Power BI

- **Imported the dataset** into Power BI.
- Created measures and calculated columns for categories such as **employment status**, **income brackets**, and **education levels**.
- Segmented the applicants by **education level** and **race/ethnicity** for a more detailed analysis.
- Used **DAX functions** to calculate percentages for employment status and income distribution.

### 3. Key Visualizations

#### Employment Status Breakdown
- **Visualized the employment distribution** of the students.
- **Purpose**: Identify how many students are unemployed, part-time, or full-time to assess the need for career support.
- **Visualization Type**: Pie chart labeled "Employment Status"

#### Income Distribution
- **Visualized the household income** distribution of students.
- **Purpose**: Assess the financial backgrounds of students and identify income brackets.
- **Visualization Type**: Bar chart labeled "Household Income."

#### Marital Status Distribution
- **Visualized the marital status** distribution of students, showing whether they are single, married, or in other relationship statuses.
- **Purpose**: Understand the marital status distribution to identify potential family responsibilities that may impact their availability for the program.
- **Visualization Type**: Bar chart labeled "Marital Status"

#### Number of Children Distribution
- **Visualized the number of children** each student has, ranging from none to 9 children.
- **Purpose**: Understand family responsibilities that may impact a student’s participation in the program.
- **Visualization Type**: Bar chart labeled "Number of Children"

#### Education Level Breakdown
- **Explored the education levels** of the applicants.
- **Purpose**: Understand the educational qualifications of the applicants, from high school to bachelor's degrees.
- **Visualization Type**: Bar chart labeled "Education Level"

#### Diversity Representation
- **Displayed the racial and ethnic composition** of the applicants.
- **Purpose**: Analyze the diversity of the applicant pool with a focus on BIPOC+ groups.
- **Visualization Type**: Pie chart labeled "Diversity Representation"

#### Number of Students per Cohort
- **Visualized the growth in cohort sizes** from 2020 to 2024.
- **Purpose**: Analyze trends in student enrollment and identify factors contributing to changes in cohort sizes.
- **Visualization Type**: Line or bar chart labeled "Number of Students per Cohort"

#### Key Performance Indicators (KPIs)
This section highlights important demographic metrics of the applicants:
- **Unemployed (30.40%)**
- **Household Income <50K (43.88%)**
- **Single Mothers (42.09%)**
- **High School / Some College (51.98%)**
- **BIPOC+ (37.23%)**

### 4. Final Dashboard
- Combined all visualizations into a comprehensive dashboard in Power BI.
- **Purpose**: Provide an overview of employment, income, education, and diversity trends for applicants to the Tech Moms program.

## Tools Used
- **Power BI**: Used for data preparation, analysis, and visualization.
- **CSV**: Cleaned dataset containing application details for the Tech Moms program.

## How to Use
1. **Open Power BI Report**: Access the report to explore the visualizations and interact with the dashboard.
2. **Explore Visualizations**: Use filters to adjust the data and focus on specific categories such as employment status or income range.
3. **Understand Insights**: Use the dashboard to identify key trends in student demographics to inform program planning and outreach.

## Key Insights

- **Employment Trends**:  
  30% of students are unemployed, suggesting a need for career development opportunities within the program.
  
- **Income Distribution**:  
  A significant portion of applicants fall into lower-income brackets, indicating the need for financial support.
  
- **Education Levels**:  
  Many students have high school or some college education, indicating the program is attracting individuals seeking further education.

- **Diversity**:  
  37.23% of applicants identify as BIPOC+, reflecting diversity within the program.

## Future Enhancements
- Incorporate additional data from future cohorts to track trends over time.
- Include metrics on post-program outcomes for a deeper analysis of the program's effectiveness.

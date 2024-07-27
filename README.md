# Salary and Specialization Analysis of Engineering Graduates

## Overview

This project involves analyzing a dataset of engineering graduates to explore various aspects such as salary distribution, job roles, and specialization preferences. The primary goals are to verify claims regarding salary ranges for specific job roles and to investigate any significant relationship between gender and specialization.

## Dataset

The dataset used for this analysis is a CSV file named `data.xlsx - Sheet1.csv` and includes the following columns:

- `ID`
- `Salary`
- `DOJ` (Date of Joining)
- `DOL` (Date of Leaving)
- `Designation`
- `JobCity`
- `Gender`
- `DOB` (Date of Birth)
- `10percentage`
- `10board`
- `12percentage`
- `12board`
- `CollegeID`
- `CollegeTier`
- `Degree`
- `Specialization`
- `collegeGPA`
- `CollegeCityID`
- `CollegeCityTier`
- `CollegeState`
- `GraduationYear`
- `English`
- `Logical`
- `Quant`
- `Domain`
- `ComputerProgramming`
- `ComputerScience`
- `MechanicalEngg`
- `ElectricalEngg`
- `TelecomEngg`
- `CivilEngg`
- `conscientiousness`
- `agreeableness`
- `extraversion`
- `neuroticism`
- `openness_to_experience`

## Data Cleaning and Preprocessing

1. **Missing Values and Duplicates:**
   - Handled missing values by replacing them with appropriate substitutes such as mean for numerical columns and mode for categorical columns.
   - Removed duplicate entries.

2. **Date Handling:**
   - Replaced 'present' with the current date in the `DOJ` and `DOL` columns.
   - Converted relevant columns to datetime format.

3. **Outlier Detection and Removal:**
   - Identified and removed outliers based on the Interquartile Range (IQR) method.

4. **Categorical Data Grouping:**
   - Grouped less frequent categories into an 'Others' category to simplify the analysis.

## Exploratory Data Analysis (EDA)

1. **Univariate Analysis:**
   - Histograms and boxplots were used to visualize the distributions of numerical columns.
   - Analyzed the distribution of categorical data using pie charts and count plots.

2. **Bivariate Analysis:**
   - Scatterplots were used to explore relationships between numerical variables and salary.
   - Correlation analysis was performed to identify significant relationships between numerical features.

## Research Questions

1. **Salary Range for Computer Science Graduates:**
   - Verified if the average salary for specific job roles (Programming Analyst, Software Engineer, Hardware Engineer, Associate Engineer) falls within the salary range of 2.5-3 lakhs as stated by a Times of India article.

2. **Gender and Specialization Relationship:**
   - Used a Chi-square test to determine if there is a significant relationship between gender and specialization preference.

## Findings

- **Salary Range Claim:** The analysis did not support the claim that Computer Science Engineering graduates in certain job roles earn 2.5-3 lakhs on average.
- **Gender and Specialization:** There was no significant relationship found between gender and specialization preference.

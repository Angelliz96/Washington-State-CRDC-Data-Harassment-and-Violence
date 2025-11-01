Washington State CRDC Data – Harassment and Violence 📄
Project Overview

This project analyzes the Civil Rights Data Collection (CRDC) – Harassment and Violence dataset for Washington State. The dataset provides information reported by school districts on incidents of harassment, bullying, and violence in schools. It includes demographic information such as race/ethnicity, gender, disability status, and English proficiency, allowing for the analysis of trends, disparities, and patterns across different student groups.

📅 Dataset Information

Data Year: 2017–18 school year

Data Last Updated: August 30, 2023

Metadata Last Updated: May 5, 2025

Date Created: August 30, 2023

Source: U.S. Department of Education, Office for Civil Rights (OCR)

Frequency: Biennial

Although the file was updated recently, it only contains data for the 2017–18 school year. The update dates reflect when the data and metadata were processed or re-published, not the addition of more recent school years.

🗂 Dataset Contents

The dataset includes:

School and district information: IDs, names, and locations

Student demographics: race/ethnicity, gender, disability status, and English proficiency

Reported incidents: type of harassment or violence and number of incidents by subgroup

Important Notes:

Data is reported directly by school districts to OCR and is not validated by OSPI, so it may differ from other official OSPI reports.

Some data is suppressed to protect student privacy.

Directory information for some schools may be incomplete if names do not match OSPI records.

🔎 Project Goals

Explore trends and disparities in harassment and violence incidents in Washington State schools.

Analyze demographic differences in reported incidents.

Visualize data through charts, graphs, and potentially interactive dashboards.

Build a reproducible analysis pipeline for educational or social impact research.

⚙️ Data Cleaning and Preparation

During the initial exploration, it was identified that approximately 1.5% of the dataset (504 rows) had "Data Not Disclosed or Unavailable" in the OrganizationLevel column and across most other fields, including identifiers and incident counts.
These records were excluded from the main analysis because they did not contain usable or verifiable information.

This decision was made to ensure data integrity and analytical clarity, while maintaining awareness of the limitations that arise from data suppression and privacy protection.

The excluded records likely represent cases where data was withheld by OCR to protect student confidentiality, particularly for small schools or low incident counts.

📊 Exploratory Data Analysis (EDA)

The project notebook includes:

Overview of dataset structure and summary statistics

Data cleaning and missing value assessment

Distribution of incidents by type and demographic group

Analysis by school, district, and county

Visualizations highlighting key patterns and trends

⚡ Tools Used

Python: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook

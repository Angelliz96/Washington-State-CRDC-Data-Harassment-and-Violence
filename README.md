Washington State CRDC Data – Harassment and Violence 📄
Project Overview

This project analyzes the Civil Rights Data Collection (CRDC) – Harassment and Violence dataset for Washington State, collected by the Office for Civil Rights (OCR) of the U.S. Department of Education. The dataset provides information reported by school districts on incidents of harassment, bullying, and violence in schools.

Important note: Due to OCR privacy policies, many data points for subgroups (race, gender, disability, etc.) are suppressed. Therefore, the analysis in this project is limited to rows where StudentGroupType == 'AllStudents', representing aggregated data for the entire school.

The dataset allows exploring general trends and patterns of incidents in Washington schools but does not allow reliable comparisons between student subgroups.

Dataset Information

Data Year: 2017–18 school year

Data Last Updated: August 30, 2023

Metadata Last Updated: May 5, 2025

Source: U.S. Department of Education, Office for Civil Rights (OCR)

Frequency: Biennial

Dataset Columns (Detailed Description)
Column	Description
County	County where the school is located (39 unique counties).
ESDName	Educational Service District (ESD) the school belongs to (12 ESDs in the dataset).
DistrictName	Name of the school district (314 unique districts).
SchoolName	Name of the school (2,159 unique schools).
CurrentSchoolType	School type: P = Pre-K, S = Elementary, I = Intermediate, A = Alternative, R = Residential, J = Junior High, 5 = Grade 5, Q = Special Program, V = Vocational, C = Charter/Other.
StudentGroupType	Type of student group: in this filtered dataset, only AllStudents.
StudentGroup	Student group name: in this filtered dataset, always AllStudents.
Allegations of harassment Based on Race/Ethnicity	Number of harassment incidents based on race/ethnicity reported at the school.
Allegations of harassment Based on Religion	Number of harassment incidents based on religion reported at the school.
Allegations of harassment Based on Sex	Number of harassment incidents based on sex reported at the school.
Allegations of harassment Based on Sexual Orientation	Number of harassment incidents based on sexual orientation reported at the school.
Allegations of harassment Based on Disability	Number of harassment incidents based on disability reported at the school.
IncidentsOfRape	Number of rape incidents reported at the school.
IncidentsOfSexualAssault	Number of sexual assault incidents reported at the school.
IncidentsOfRobberyWithWeapon	Number of robbery incidents with a weapon reported at the school.
IncidentsOfRobberyWithFirearmOrExplosive	Number of robbery incidents with a firearm or explosive reported at the school.
IncidentsOfRobberyWithoutWeapon	Number of robbery incidents without a weapon reported at the school.
IncidentsOfAttackWithWeapon	Number of attack incidents with a weapon reported at the school.
IncidentsOfAttackWithFirearmOrExplosive	Number of attack incidents with a firearm or explosive reported at the school.
IncidentsOfAttackWithoutWeapon	Number of attack incidents without a weapon reported at the school.
IncidentsOfThreatAttackWithWeapon	Number of threat of attack incidents with a weapon reported at the school.
IncidentsOfThreatAttackWithFirearmOrExplosive	Number of threat of attack incidents with a firearm or explosive reported at the school.
IncidentsOfThreatAttackWithoutWeapon	Number of threat of attack incidents without a weapon reported at the school.
IncidentsOfPosessionFireamOrExplosive	Number of incidents of possession of a firearm or explosive reported at the school.
Data Cleaning and Preparation

Only rows with StudentGroupType == 'AllStudents' were kept, as these are the only rows with real numeric values.

This ensures that the final dataset contains only reliable aggregated school-level data, eliminating rows with suppressed or unavailable data.

Exploratory Data Analysis (EDA)

The project notebook includes:

Dataset structure and summary statistics.

Distribution of incidents by harassment and violence type.

Comparison of incidents by school, district, and county.

Visualizations: bar charts, histograms, and maps by county.

Tools Used

Python: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Environment: Jupyter Notebook

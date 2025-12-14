Falcon 9 First Stage Landing Prediction – Capstone Project

Project Overview:
This project aims to predict whether the Falcon 9 first stage will land successfully. Success in landing affects launch costs and the feasibility of reusable rockets. The analysis explores SpaceX launch data, booster performance, payloads, and launch site characteristics.

Methodology:
Data collection and cleaning from SpaceX launch records
Exploratory Data Analysis (EDA) using Python (pandas, matplotlib, seaborn)
Geospatial analysis of launch sites with Folium
Machine Learning models: Logistic Regression, SVM, Decision Tree, KNN
Hyperparameter tuning with GridSearchCV
Model evaluation with test accuracy and confusion matrices

Key Results:
Four main launch sites: CCAFS LC-40, VAFB SLC-4E, KSC LC-39A, CCAFS SLC-40
Launch sites are near the coast and far from cities/railways/highways for safety
KSC LC-39A had the highest success ratio (76.9%)
Higher flight numbers → higher first stage landing success
Overall: 61 successful launches vs. 40 failures
Payloads 2,000–6,000 kg and boosters FT & B4 → higher landing success
Multiple Block 5 boosters carried maximum payload (15,600 kg)
Best ML models: Logistic Regression, SVM, KNN (~83% accuracy); Decision Tree (~78%)
Logistic Regression shows good class separation with few false positives
Success rate increased steadily from 2013 to 2020
First successful drone ship landing: 2016-04-08

Insights:
Booster type and payload mass are key factors in successful landing
Launch site location and orbit type impact landing success
Machine Learning can reliably predict landing outcomes, guiding operational planning

Project Files:
Jupyter Notebooks with data analysis and model building

Of course\! Here is a README file for your Hospital Emergency Room Analysis project.

-----

# Hospital Emergency Room Analysis Dashboard


## 🏥 Project Overview

This project involves the creation of a comprehensive Power BI dashboard to analyze the performance of a hospital's Emergency Room (ER). The primary goal is to provide actionable insights into patient management, operational efficiency, and service quality. By tracking key performance indicators (KPIs), the dashboard enables stakeholders to make data-driven decisions to optimize resource allocation, reduce wait times, and enhance patient satisfaction.

-----

## 🎯 Business Requirements

The core objective was to develop a dynamic dashboard to monitor and analyze ER activities. Key requirements included:

  * Tracking the total number of patients, average wait times, and patient satisfaction scores.
  * Analyzing patient demographics by age, gender, and race.
  * Monitoring patient admission rates and department referral patterns.
  * Identifying peak busy hours and days to optimize staffing.
  * Providing granular, patient-level details for in-depth analysis.

-----

## 📊 Data Source

The analysis is based on a single CSV file:

  * **File:** `Hospital ER_Data.csv`
  * **Description:** This dataset contains anonymized patient records from the ER, including demographic information, admission details, wait times, satisfaction scores, and referral data. A detailed explanation of each field is available in the `Data Terminology.pdf` file.

-----

## 🛠️ Tools Used

  * **Microsoft Power BI:** Used for data connection, cleaning (Power Query), modeling, creating DAX calculations, and developing the interactive dashboard.
  * **DAX (Data Analysis Expressions):** Used to create custom measures and calculated columns for KPIs like Average Wait Time, Patient Satisfaction Score, and Admission Rate.

-----

## ⚙️ Project Methodology

The project followed a structured approach from data to insights:

1.  **Requirement Gathering:** Defined KPIs and business questions with stakeholders.
2.  **Data Cleaning & Transformation:** Used Power Query to handle missing values, correct data types, and structure the data for analysis.
3.  **Data Modeling:** Established relationships between different data tables to create a robust model.
4.  **DAX Calculations:** Developed DAX measures to calculate key metrics required for the visualizations.
5.  **Dashboard Development:** Designed four distinct dashboard pages in Power BI:
      * **Monthly View:** A snapshot of performance for a selected month.
      * **Consolidated View:** An aggregated view with a customizable date range for trend analysis.
      * **Patient Details:** A detailed grid view for drilling down into individual patient data.
      * **Key Takeaways:** A summary of the most critical insights and findings.
6.  **Insights Generation:** Analyzed the completed dashboard to derive actionable recommendations.

-----

## Key Insights

The dashboard revealed several important patterns and trends:

  * **Peak Periods:** The busiest days were identified as **Mondays, Saturdays, and Tuesdays**. Peak hours were concentrated around **11 AM, 1 PM, 7 PM, and 11 PM**, indicating a need for increased staffing during these times.
  * **Patient Demographics:** The largest patient age group was **Adults (30-39 years)**, followed by Young Adults (20-29 years). The patient population is racially diverse, with **White** and **African American** being the largest groups.
  * **Department Referrals:** A significant number of patients did not require a referral. For those who did, **General Practice** and **Orthopedics** were the most common destinations.
  * **Admission Patterns:** The admission rate was nearly **50%**, with almost half of the ER patients being admitted to the hospital for further care.
  * **Patient Satisfaction:** The average patient satisfaction score was moderate, suggesting areas for improvement in patient experience, potentially linked to wait times.

-----

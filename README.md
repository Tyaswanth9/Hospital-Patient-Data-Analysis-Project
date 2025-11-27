# Hospital-Patient-Data-Analysis-Project

## Overview

This project analyzes Emergency Room (ER) data to track patient flow, service quality, and operational performance.
I combined multiple data sources into a single data model and created interactive Power BI dashboards showing daily, monthly, and consolidated views.

Key insights include:

Daily patient visits and wait times

Patient satisfaction trends

Department referrals

Patient demographics and admission status

These dashboards help hospital staff quickly understand trends, identify issues, and make better operational decisions.

---

## Business Problem

ERs often face challenges like long wait times, overcrowding, limited resources, and low patient satisfaction.
Without clear data, it’s hard to know when to allocate staff, which departments have high referrals, or why satisfaction drops.

This project addresses these problems by providing dashboards that visualize trends, wait times, referrals, satisfaction, and patient details—helping hospitals improve care and efficiency.



---

## Data Source Information

This project uses the following 6 data files:

- `patient_data.csv`
- `Patient_safisfaction_score.csv`
- `patient_department referral.csv`
- `patient_waiting.csv`
- `patient_racet.csv`
- `patient_admmission status.csv`


---

## Data Cleaning Process

- Imported all six files into Power Query.
- Created new columns from existing data, e.g., Admission Status.
- Split Patient Name into First Name and Last Name.
- Separated Admission DateTime into Date and Time (24-hour format).
- Built data model using a common column to connect tables.
- Checked and fixed duplicates, missing values, and inconsistencies.

---

## Data Modeling

![Data Modeling Diagram](https://github.com/Tyaswanth9/Hospital-Patient-Data-Analysis-Project/blob/myself/data%20modeling.png)

*Image: data model showing relationships between datasets*

---

## Tools and Technologies Used


- Power BI


---

## Key Insights Included

- No of patients
- Average waiting time
- Average patient saticfation score
- NO of patinet Reffered


---

## Power BI

### Dashboard Features

- Clean, colorful visualizations
- Interactive reports with filters and slicers
- Documentation explaining design and data sources
- Sample datasets used in reports

### Dashboard Image

![Power BI Dashboard_1](https://github.com/Tyaswanth9/Hospital-Patient-Data-Analysis-Project/blob/myself/power%20bi%20dashboard_1.png)

![Power BI Dashboard_2](https://github.com/Tyaswanth9/Hospital-Patient-Data-Analysis-Project/blob/myself/power%20bi%20dashboard_2.png)

![Power BI Dashboard_3](https://github.com/Tyaswanth9/Hospital-Patient-Data-Analysis-Project/blob/myself/power%20bi%20dashboard_3.png)

---

## What I Did 

- Combined data from six files into a single data model.
- Built calendar tables using the CALENDARAUTO() DAX function.
- Used DAX formulas to calculate KPIs and measures 
- Designed visual charts and dashboards.
- Added filters and slicers for improved interaction.
-Used page navigation buttons to easily move from one page to another.

---

## What I Learned 

- Improved my ability to combine multiple data sources into a single, well-structured data model.
- Enhanced my understanding of creating calendar tables using CALENDARAUTO().
- Strengthened my DAX skills by writing formulas to calculate KPIs and measures.
- Developed better skills in designing clean, interactive, and user-friendly Power BI dashboards.
- Improved my knowledge of using slicers, filters, and page navigation to create a smooth user experience.

 ---

**Note: This code is provided for reference only - do not for use , copy , modify , or distributions, or reproduction.**

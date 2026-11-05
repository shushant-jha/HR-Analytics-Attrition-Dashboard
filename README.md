# HR Analytics \& Attrition Dashboard

A Tableau project focused on exploring workforce data and presenting HR
information through an interactive, multi-view dashboard.

## Project Overview

I created this dashboard using **Tableau** to make HR data easier to
explore and understand. It brings workforce information together in one
place, covering employee numbers, demographics, departments, locations,
education, performance, and salary.

The dashboard is organised into two views:

* **HR Summary:** A high-level overview of the workforce.
* **HR Details:** An employee-level table with filters to explore
individual records.

## Dashboard Preview

### HR Summary

!\[HR Dashboard Summary](Images/HR%20Summary%20.png)

### HR Details

!\[HR Dashboard Details](Images/HR%20Details.png)

## What the Dashboard Covers

### 1\. Workforce Overview

* Active employee count
* Total employees hired
* Employees terminated
* Department-wise employee distribution
* Location-wise workforce distribution

### 2\. Employee Demographics

* Gender distribution
* Education level and age group
* Education level and performance rating

### 3\. Income Analysis

* Salary by education level and gender
* Relationship between age and salary
* Salary patterns across job roles

### 4\. Employee Details

The Details view includes employee-level fields such as:

* Employee ID
* Employee name
* Job title
* Department
* Location
* Salary
* Employment status
* Hire date
* Length of employment

Filters allow users to narrow down the employee records.

## Dataset Overview

The project uses a **dummy (synthetic) HR dataset** supplied in an Excel
workbook. The source workbook contains **8,950 records and 14 columns**.

The dataset includes fields such as:

* Employee ID and employee name
* Gender, state, and city
* Education level and birthdate
* Hire date and termination date
* Department and job title
* Salary and performance rating

### Workforce Summary

Metric                   Count

\---

Active Employees         7,984
Total Hires              8,950
Terminated Employees       966

**Data note:** The dataset is dummy/synthetic data and is included for
project demonstration and learning purposes. It does not contain real
employee personal or confidential information.

## Tools Used

* **Tableau** --- dashboard development, data visualization, and
interactive data exploration.
* **Microsoft Excel** --- source dataset workbook.

## Repository Structure

``` text
HR-Analytics-Attrition-Dashboard/
│
├── Dashboard/
│   └── HR Analytics.twbx
│
├── Dataset/
│   └── Dataset.xlsx
│
├── Images/
│   ├── HR Summary .png
│   ├── HR Details.png
│   └── HR Dashboard.mp4
│
└── README.md
```

## Project Files

* **Tableau Workbook:**
[`Dashboard/HR Analytics.twbx`](Dashboard/HR%20Analytics.twbx)
* **Source Dataset:** [`Dataset/Dataset.xlsx`](Dataset/Dataset.xlsx)
* **HR Summary Screenshot:**
[`Images/HR Summary .png`](Images/HR%20Summary%20.png)
* **HR Details Screenshot:**
[`Images/HR Details.png`](Images/HR%20Details.png)
* **Dashboard Walkthrough Video:**
[`Images/HR Dashboard.mp4`](Images/HR%20Dashboard.mp4)

## Key Learnings

While working on this project, I practised:

* Building a multi-view dashboard in Tableau.
* Presenting HR information through different chart types.
* Using filters to explore workforce data.
* Exploring workforce trends through visual analysis.
* Presenting information in a way that is easier to understand.

## How to Explore This Project

1. Review the dashboard screenshots in the **Dashboard Preview**
section.
2. Open or download the Tableau workbook from the `Dashboard` folder.
3. Refer to the Excel workbook in the `Dataset` folder for the dummy
source data.
4. Watch the dashboard walkthrough video in the `Images` folder.

To interact with the dashboard, open the `.twbx` workbook in Tableau.

\---

Thank you for taking the time to explore my project!


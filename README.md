#  Medical Data Cleaning and Dashboard Analysis

##  Overview

This project focuses on cleaning, transforming, and analyzing healthcare data to derive actionable insights through interactive dashboards. It uses three datasets — *Healthcare Facts*, *Doctors Dimension*, and *Hospitals Dimension* — and integrates them using a relational data model (star schema) for in-depth healthcare analytics.

---

##  Objectives

- Clean and standardize raw medical data for consistency.
- Transform data to create new analytical features (e.g., Length of Stay).
- Integrate datasets using Power Pivot for relational modeling.
- Visualize medical, financial, and operational insights using dashboards.

---

##  Dataset Description

- **Healthcare Facts**: Central fact table with patient details, blood type, medical condition, admission type, etc.
- **Doctors Dimension**: Contains doctor IDs and full names.
- **Hospitals Dimension**: Lists hospital IDs and hospital names.

---

##  Data Challenges

- Inconsistent entries (e.g., `'M'` vs `'Male'`, `'normal'` vs `'Normal'`)
- Missing values (Doctor IDs, Medical Conditions)
- Duplicate records for patients
- Mixed date formats (e.g., `'DD-MM-YYYY'`, `'MM/DD/YYYY'`)
- Invalid categorical values (e.g., `'Unknown'`, `'N/A'`)
- Numeric fields stored as text

---

##  Data Transformation Process

###  Power Query
- Removed/imputed missing values
- Standardized inconsistent values
- Created derived columns (Length of Stay, Year, Quarter, Month)
- Combined first and last name into Full Name
- Assigned unique Patient IDs

###  Power Pivot
- Modeled relationships between fact and dimension tables
- Created unified model for dashboard analysis

---

##  Dashboard Insights

###  Medical Insights
- Patient condition trends
- Admission types
- Average length of stay

###  Financial Analysis
- Total billing: `$276,155,967` (2019–2024)
- Yearly billing trends
- Hospital-level breakdowns

###  Sales/Utilization Metrics
- 14 doctors’ workload
- Hospital service utilization
- Average stay: `16 days`

---

##  Key Metrics

-  Total Patients: **10,116**
-  Number of Doctors: **14**
-  Average Length of Stay: **16 Days**
-  Total Billing: **$276,155,967**

---

##  Tools Used

- **Power Query** – Data cleaning and transformation
- **Power Pivot** – Data modeling and integration
- **Excel / Power BI** – Dashboard development and visualization



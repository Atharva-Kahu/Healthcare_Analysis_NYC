# 🏥 Healthcare Analytics Dashboard

This Power BI dashboard analyzes patient demographics, clinical outcomes, and cost data from hospital inpatient discharges for **Total Hip Replacement** surgeries in New York State. The insights help stakeholders identify trends in care delivery, cost efficiency, and patient risk factors across counties and facilities.

---

## 📊 Dashboard Features

The dashboard includes multiple visualizations to provide a comprehensive view of the dataset:

### 🔹 Key Performance Indicators (KPIs)
- Total Discharges
- Average Length of Stay
- Average Total Charges
- Average Total Costs

### 🔹 Demographics and Outcomes
- **Stacked Column Chart**: Discharges by Age Group and Gender
- **Pie/Donut Charts**:
  - Ethnicity Breakdown
  - APR Risk of Mortality

### 🔹 Cost & Facility Analysis
- **Bar Charts**:
  - Average Cost by Hospital
  - Total Discharges by County
  - Average Length of Stay by Facility

## 📁 Dataset

- **Source**: Centers for Medicare & Medicaid Services (CMS) – Public Hospital Data
- **File Used**: `hospital_inpatient_discharges_totalhipreplacement.csv`
- **Rows**: ~26,000 records
- **Key Columns**:
  - Demographics: `age_group`, `gender`, `ethnicity`, `race`
  - Location: `hospital_county`, `facility_name`
  - Clinical: `apr_severity_of_illness_description`, `patient_disposition`
  - Cost: `total_charges`, `total_costs`, `length_of_stay`

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query Editor**
- **Data Visualization & Filtering**
- **Custom Tooltips and Interactive Slicers**

---

## 📈 Insights & Use Cases

- Identify **high-cost counties or hospitals**
- Understand **risk and severity distributions**
- Compare **outcomes across age, gender, and ethnicity**
- Monitor **cost efficiency** in hip replacement procedures

This dashboard can assist **healthcare administrators, public health analysts, and policymakers** in optimizing resources and improving patient care quality.
![image](https://github.com/user-attachments/assets/73447b11-2ffd-4e17-af22-5ac7a5def0cc)


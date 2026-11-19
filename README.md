# 🏥 Hospital Data Analysis | Python & Power BI

## 📌 Project Overview

This project focuses on analyzing hospital healthcare data to gain insights into patient demographics, emergency visits, hospital admissions, discharge patterns, and healthcare services.

The project uses **Python for data cleaning and preprocessing** and **Microsoft Power BI for interactive data visualization and dashboard development**.

The objective is to transform raw hospital data into meaningful insights that can help understand hospital operations and patient visit trends.

## 🎯 Project Objectives

- Analyze patient demographics and hospital visits.
- Understand emergency department visit patterns.
- Identify common reasons for emergency visits.
- Analyze hospital admissions and discharge trends.
- Explore healthcare services and emergency dispositions.
- Develop an interactive Power BI dashboard for data-driven insights.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data cleaning and analysis |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Data analysis |
| Microsoft Power BI | Interactive dashboard |
| Microsoft Excel | Dataset management |

## 📂 Dataset Description

The hospital dataset contains seven sheets:

1. **Patients** – Patient demographics and personal information.
2. **EDVisits** – Emergency department visit records.
3. **AmbulatoryVisits** – Outpatient and ambulatory visit information.
4. **ReAdmissionRegistry** – Hospital admission and readmission details.
5. **Discharges** – Patient discharge records.
6. **Providers** – Healthcare provider information.
7. **EDUnique** – Emergency department visit details.

## 🔍 Project Workflow

### 1. Data Loading
- Imported hospital datasets using Pandas.
- Loaded multiple Excel sheets into individual DataFrames.
- Inspected dataset dimensions and column information.

### 2. Data Cleaning & Preprocessing
- Checked missing values and duplicate records.
- Removed duplicate rows.
- Standardized column names.
- Cleaned text fields and categorical values.
- Converted date and time columns into appropriate formats.
- Validated primary keys and patient ID relationships.

### 3. Feature Engineering
Created additional analytical features:

- **Actual Length of Stay:** Calculated the duration between admission and discharge.
- **Length of Stay Category:** Classified hospital stays into Short Stay, Medium Stay, and Long Stay.
- **Patient Age:** Calculated patient age using date of birth and visit date.
- **Age Groups:** Categorized patients into different age groups.

### 4. Exploratory Data Analysis (EDA)
- Examined patient demographics.
- Analyzed emergency visit acuity.
- Explored reasons for emergency visits.
- Studied hospital admissions and discharge patterns.
- Investigated missing values and data quality.

### 5. Power BI Dashboard

Developed an interactive hospital analytics dashboard featuring:

- Total Patients
- Total Emergency Visits
- Total Hospital Admissions
- Emergency Visit Reasons
- Admissions by Healthcare Service
- Emergency Department Disposition
- Hospital Data Source Distribution

The dashboard provides a visual overview of hospital operations and patient activity.

## 📊 Key Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Data Manipulation
- Feature Engineering
- Data Validation
- Data Visualization
- Dashboard Development
- Healthcare Data Analytics
- Business Intelligence

## 📁 Project Structure

```text
Hospital-Data-Analysis/
│
├── Hospital_Data_Analysis.ipynb
│
├── HospitalDatabase.xlsx
│
├── HospitalData1.pbix
│
└── README.md
```

## 🚀 How to Run the Project

### Python Analysis

1. Clone this repository:

```bash
git clone https://github.com/your-username/Hospital-Data-Analysis.git
```

2. Navigate to the project folder:

```bash
cd Hospital-Data-Analysis
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Hospital_Data_Analysis.ipynb` and execute the cells.

### Power BI Dashboard

1. Install Microsoft Power BI Desktop.
2. Download the `.pbix` file from this repository.
3. Open it using Power BI Desktop.
4. Explore the dashboard and its visualizations.

## 💡 Project Outcome

Successfully developed a healthcare data analytics project by combining Python-based data preprocessing and Power BI dashboard development.

This project demonstrates how raw hospital datasets can be cleaned, transformed, analyzed, and presented through meaningful visualizations to support healthcare data analysis.


⭐ If you find this project interesting, feel free to star the repository!

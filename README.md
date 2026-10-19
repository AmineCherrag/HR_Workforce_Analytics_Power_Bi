# 👥 HR Workforce Overview: Power BI Dashboard

An interactive Power BI dashboard that gives HR leaders a one-page view of headcount, satisfaction, tenure, salary, and turnover, filterable by **Year**, **Department**, and **Location**.

<img width="1311" height="733" alt="Screenshot 2026-10-17 013527" src="https://github.com/user-attachments/assets/9ef985b6-3f5a-458b-b0a7-dfaeea59a174" />

## 📊 What's Inside

**KPIs:** 798 active employees · 3.33 avg satisfaction · 7 yrs 10 mos avg tenure · 82.23K avg salary · 20.20% turnover

**Visuals:**
- Employees by Department (bar chart)
- Employees by Location (column chart)
- Age–Salary Relationship (scatter plot with trend line)
- Age Group Distribution (histogram)
- Median vs Average Salary by Department (clustered columns)

## 🔍 Key Insights

- Headcount is evenly spread across departments and locations; Chicago is the largest site.
- Most employees are aged 30–49.
- Salary rises with age, but the wide spread shows role and level matter too.
- Engineering pays the most (~116K avg) and Customer Support the least (~55K).
- IT's average salary (~101K) is well above its median (~90K), pointing to a few high earners.
- A 20.20% turnover rate is worth investigating by department and location.

## 🛠️ Skills Demonstrated

- **Python (pandas):** data cleaning, handling missing values and duplicates, feature engineering (age groups, tenure)
- **Data modeling:** building a clean model for analysis
- **DAX:** measures for headcount, salary, tenure, satisfaction, and turnover
- **Data visualization:** choosing the right chart for each question, KPI cards, trend line, clean layout
- **Interactivity:** slicers and cross-filtering between visuals

## 🧰 Tools

Python (pandas, NumPy) · Jupyter Notebook · Power BI Desktop · DAX

## 📁 Structure

```
├── HR_Workforce_Overview.pbix
├── data/                  # raw and cleaned CSV files
├── notebooks/             # Python cleaning notebook
├── images/dashboard.png
└── README.md
```

## 🚀 How to Use

1. Download this repository.
2. Open `HR_Workforce_Overview.pbix` in Power BI Desktop.
3. Update the data source path if prompted, then explore using the slicers.

## 👤 Author

**Your Name** · [LinkedIn](https://linkedin.com/in/your-profile) · [GitHub](https://github.com/your-username)

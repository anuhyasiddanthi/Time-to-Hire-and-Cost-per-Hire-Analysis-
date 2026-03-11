# 📊 Time-to-Hire & Cost-per-Hire Analysis in HR Recruitment

![Tools Used](https://img.shields.io/badge/Tools-Excel%20%7C%20Python%20%7C%20Power%20BI%20%7C%20Scikit--learn-blue)

## 📖 Overview

This project analyzes the efficiency and financial impact of recruitment processes by evaluating two critical HR metrics: **Time-to-Hire (TTH)** and **Cost-per-Hire (CPH)**. Using historical recruitment data from **2018–2024**, the analysis identifies hiring bottlenecks, evaluates recruiter performance, and predicts future hiring trends.

The project evaluates key recruitment metrics including **department-wise hiring duration**, **job role hiring costs**, **recruiter performance**, and **recruitment stage delays** to generate insights that support **data-driven recruitment decisions**.

This project showcases an **end-to-end HR analytics workflow**, from **data preprocessing and exploratory data analysis in Python** to **predictive modeling and dashboard visualization in Power BI**.

---

## 🎯 Objectives

- Analyze the **average Time-to-Hire and Cost-per-Hire** across the recruitment pipeline  
- Identify **hiring bottlenecks across departments and job roles**  
- Compare **recruiter-wise hiring performance** using historical recruitment data  
- Perform **trend analysis (2018–2024)** to evaluate recruitment efficiency  
- Forecast **Time-to-Hire and Cost-per-Hire for 2025–2026** using predictive modeling  
- Provide **data-driven recommendations** to improve recruitment efficiency  

---

## 🛠️ Project Workflow & Tools

This project follows a structured workflow using multiple tools to manage the **complete data analytics pipeline** from data preparation to visualization.

| Phase | Tool | Role |
|------|------|------|
| **1. Data Preparation** | Excel, Python (Pandas) | Cleaning and structuring recruitment datasets |
| **2. Data Analysis** | Python (Pandas, NumPy) | Calculating Time-to-Hire and Cost-per-Hire metrics |
| **3. Exploratory Data Analysis** | Matplotlib, Seaborn | Visualizing recruitment trends and hiring delays |
| **4. Predictive Modeling** | Scikit-learn | Forecasting recruitment metrics for 2025–2026 |
| **5. Visualization** | Power BI | Building interactive recruitment dashboards |

---

## 📊 Methodology

### Data Preparation

Recruitment datasets were cleaned and standardized using **Python (Pandas)**.

Key preprocessing steps included:

- Converting recruitment dates into **datetime format**
- Calculating **Time-to-Hire** using the difference between **Job Posted Date and Joining Date**
- Aggregating recruitment cost components including:

  - Advertising Cost  
  - Agency Fee  
  - Interview Cost  
  - Relocation Cost  
  - Onboarding Cost  

The processed dataset was used for **exploratory analysis and predictive modeling**.

---

### Exploratory Data Analysis (EDA)

EDA was performed to identify **hiring patterns, recruitment delays, and cost variations**.

Key analyses included:

- **Department-wise hiring analysis**
- **Job role hiring duration comparisons**
- **Recruitment cost distribution**
- **Recruiter performance evaluation**

Visualization techniques included:

- Bar charts
- Histograms
- Trend analysis plots

These insights helped identify **roles and departments with longer hiring durations and higher recruitment costs**.

---

### Predictive Modeling

Predictive models were developed using **Linear Regression (Scikit-learn)** to forecast recruitment metrics.

The models predicted:

- **Time-to-Hire for 2025–2026**
- **Cost-per-Hire for 2025–2026**

Model performance was evaluated using the **R² score**, achieving approximately **92% predictive accuracy**.

---

### Dashboard Development

An **interactive Power BI dashboard** was created to visualize recruitment insights including:

- Average **Time-to-Hire**
- Average **Cost-per-Hire**
- **Recruiter performance comparison**
- **Department-wise hiring trends**
- **Job role hiring comparisons**

These dashboards enable **HR teams to monitor recruitment efficiency and make data-driven decisions**.

---

## 📈 Results & Key Insights

### Recruitment Metrics

- Total candidates analyzed: **120+**
- Average **Time-to-Hire:** **95.53 days**
- Average **Cost-per-Hire:** **₹64,640**

### Job Title Insights

- Fastest hiring role: **Software Developer – 84 days**
- Slowest hiring role: **Reporting Analyst – 104 days**
- Lowest cost per hire: **Social Media Coordinator – ₹55,000**
- Highest cost per hire: **Sales Manager – ₹81,000**

### Department Insights

- Fastest hiring department: **Sales – 88 days**
- Slowest hiring department: **BPO – 98 days**
- Lowest hiring cost: **BPO – ₹58,000**
- Highest hiring cost: **Sales – ₹74,000**

### Recruitment Stage Insights

Training and onboarding processes accounted for nearly **50% of the recruitment timeline**, highlighting a key opportunity for **process optimization**.

---

## 🔮 Predictive Insights (2025–2026)

### Average Predicted Time-to-Hire

- **2025:** 97.33 days  
- **2026:** 97.72 days  

### Average Predicted Cost-per-Hire

- **2025:** ₹68,997  
- **2026:** ₹69,704  

### Job Role Predictions

- Fastest hiring role: **AI/ML Engineer**
- Slowest hiring role: **Automation Tester**

### Recruiter Predictions

- Fastest recruiter: **Recruiter A**
- Lowest hiring cost recruiter: **Recruiter C**

These predictions support **future workforce planning and recruiter allocation strategies**.

---

## 💡 Recommendations

- Streamline **interview and approval processes** for high-delay roles  
- Reduce recruitment costs through **internal referrals**  
- Assign **high-performing recruiters** to complex job roles  
- Implement **predictive hiring strategies** to anticipate recruitment demand  
- Use **interactive dashboards** for continuous recruitment performance monitoring  

---

## 📂 Repository Structure

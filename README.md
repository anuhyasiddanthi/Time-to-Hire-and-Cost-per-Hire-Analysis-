📊 Time to Hire and Cost per Hire Analysis in HR Recruitment
📖 Overview

This project analyzes the efficiency and financial impact of recruitment processes by evaluating two critical HR metrics: Time to Hire (TTH) and Cost per Hire (CPH). Using historical recruitment data from 2018–2024, the analysis identifies hiring bottlenecks, evaluates recruiter performance, and predicts future hiring trends.

The project integrates data analysis, predictive modeling, and interactive dashboards to support data-driven recruitment strategies. By leveraging tools such as Python, Excel, and Power BI, the study provides actionable insights that help organizations optimize recruitment timelines and manage hiring costs effectively.

The project demonstrates an end-to-end HR analytics workflow, including data preprocessing, exploratory analysis, predictive modeling, and dashboard visualization.

🎯 Objectives

Analyze the average Time to Hire and Cost per Hire across the recruitment pipeline.

Identify hiring bottlenecks across departments and job roles.

Compare recruiter-wise hiring performance using historical data.

Perform trend analysis (2018–2024) to evaluate recruitment efficiency.

Forecast Time to Hire and Cost per Hire for 2025–2026 using predictive modeling.

Provide data-driven recommendations to improve recruitment efficiency.

🛠️ Tools & Technologies Used
Tool	Purpose
Excel	Data preprocessing and initial analysis
Python (Pandas, NumPy)	Data cleaning and manipulation
Python (Matplotlib, Seaborn)	Exploratory data visualization
Scikit-learn	Predictive modeling (Linear Regression)
Power BI	Interactive dashboards and KPI visualization
🔄 Project Workflow

This project follows a structured data analytics pipeline from raw data processing to visualization.

Phase	Tool	Role
Data Preparation	Excel, Python	Cleaning and structuring recruitment data
Data Analysis	Python (Pandas)	Calculating Time to Hire and Cost per Hire
Exploratory Data Analysis	Matplotlib, Seaborn	Identifying hiring trends and patterns
Predictive Modeling	Scikit-learn	Forecasting hiring metrics for 2025–2026
Dashboarding	Power BI	Visualizing KPIs and recruitment insights
📊 Methodology
Data Preparation

Cleaned and standardized recruitment data using Python (Pandas).

Converted raw recruitment dates into datetime format for accurate calculations.

Computed Time to Hire using the difference between Job Posted Date and Joining Date.

Aggregated recruitment cost components such as:

Advertising cost

Agency fee

Interview cost

Relocation cost

Onboarding cost

Exploratory Data Analysis (EDA)

Conducted department-wise and job title-wise analysis.

Identified roles with longer hiring durations and higher recruitment costs.

Used visualizations such as histograms, bar charts, and trend plots to explore patterns.

Predictive Modeling

Built Linear Regression models using Scikit-learn to forecast:

Time to Hire (2025–2026)

Cost per Hire (2025–2026)

Model performance was evaluated using the R² score, achieving approximately 92% predictive accuracy.

Dashboard Development

Created Power BI dashboards to visualize key recruitment metrics:

Average Time to Hire

Average Cost per Hire

Recruiter performance

Department-wise hiring trends

Job title hiring comparisons

📈 Results & Key Insights
Recruitment Metrics

Total candidates analyzed: 120+

Average Time to Hire: 95.53 days

Average Cost per Hire: ₹64,640

Job Title Insights

Fastest hiring role: Software Developer – 84 days

Slowest hiring role: Reporting Analyst – 104 days

Lowest cost per hire: Social Media Coordinator – ₹55,000

Highest cost per hire: Sales Manager – ₹81,000

Department Insights

Fastest hiring department: Sales – 88 days

Slowest hiring department: BPO – 98 days

Lowest hiring cost: BPO – ₹58,000

Highest hiring cost: Sales – ₹74,000

Recruitment Stage Analysis

Training and onboarding processes accounted for nearly 50% of the total recruitment timeline, indicating a key area for optimization.

🔮 Predictive Insights (2025–2026)
Average Predicted Time to Hire

2025: 97.33 days

2026: 97.72 days

Average Predicted Cost per Hire

2025: ₹68,997

2026: ₹69,704

Job Role Predictions

Fastest hiring role: AI/ML Engineer

Slowest hiring role: Automation Tester

Recruiter Performance Predictions

Fastest recruiter: Recruiter A

Lowest hiring cost recruiter: Recruiter C

These predictions support future workforce planning and recruiter allocation strategies.

💡 Recommendations

Optimize high-delay roles by streamlining interview and approval processes.

Reduce recruitment costs by increasing internal referrals and reducing agency reliance.

Leverage high-performing recruiters for complex job roles.

Implement predictive hiring strategies to anticipate recruitment demand.

Use data-driven dashboards for continuous recruitment performance monitoring.

📂 Repository Structure
.
Repository
│
├── data
├── notebooks
│   └── HR_Recruitment_Analysis.ipynb
├── dashboard
└── README.md

📊 Dashboard Preview

Below is the Power BI dashboard visualizing recruitment insights.

(Add your Power BI dashboard screenshot here)

Example:

![Recruitment Dashboard](images/dashboard.png)
📚 References

Native Techies Pvt. Ltd.

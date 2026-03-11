📊 Time to Hire and Cost per Hire Analysis in HR Recruitment
🛠️ Tools Used

Excel – Data preprocessing and initial analysis

Python (Pandas, NumPy) – Data cleaning and manipulation

Python (Matplotlib, Seaborn) – Exploratory data visualization

Scikit-learn – Predictive modeling (Linear Regression)

Power BI – Interactive dashboards and KPI visualization

📖 Overview

This project analyzes the efficiency and financial impact of recruitment processes by evaluating two critical HR metrics: Time to Hire (TTH) and Cost per Hire (CPH). Using historical recruitment data from 2018–2024, the analysis identifies hiring bottlenecks, evaluates recruiter performance, and predicts future hiring trends.

The project integrates data analysis, predictive modeling, and interactive dashboards to support data-driven recruitment strategies. By leveraging tools such as Python, Excel, and Power BI, the study provides actionable insights that help organizations optimize recruitment timelines and manage hiring costs effectively.

This project demonstrates an end-to-end HR analytics workflow, including data preprocessing, exploratory analysis, predictive modeling, and dashboard visualization.

🎯 Objectives

Analyze the average Time to Hire and Cost per Hire across the recruitment pipeline.

Identify hiring bottlenecks across departments and job roles.

Compare recruiter-wise hiring performance using historical data.

Perform trend analysis (2018–2024) to evaluate recruitment efficiency.

Forecast Time to Hire and Cost per Hire for 2025–2026 using predictive modeling.

Provide data-driven recommendations to improve recruitment efficiency.

🛠️ Project Workflow & Tools

This project follows a structured data analytics workflow, moving from raw data processing to predictive modeling and dashboard visualization.

Phase	Tool	Role
Data Preparation	Excel, Python	Cleaning and structuring recruitment data
Data Analysis	Python (Pandas)	Calculating Time to Hire and Cost per Hire
Exploratory Data Analysis	Matplotlib, Seaborn	Identifying hiring trends and patterns
Predictive Modeling	Scikit-learn	Forecasting hiring metrics for 2025–2026
Dashboarding	Power BI	Visualizing KPIs and recruitment insights
📊 Methodology
Data Preparation

Raw recruitment data was cleaned and standardized using Python (Pandas).

Key preprocessing steps included:

Converting recruitment dates into datetime format

Calculating Time to Hire using the difference between Job Posted Date and Joining Date

Aggregating recruitment cost components such as:

Advertising cost

Agency fees

Interview costs

Relocation costs

Onboarding costs

Exploratory Data Analysis (EDA)

EDA was performed to identify patterns, delays, and cost variations in the recruitment pipeline.

Analysis included:

Department-wise hiring analysis

Job title hiring duration comparisons

Recruitment cost distribution analysis

Visualization techniques included:

Bar charts

Histograms

Trend analysis plots

These insights helped identify roles and departments with higher hiring delays or recruitment costs.

Predictive Modeling

To forecast future recruitment metrics, Linear Regression models were developed using Scikit-learn.

The models predicted:

Time to Hire for 2025–2026

Cost per Hire for 2025–2026

Model performance was evaluated using the R² score, achieving approximately 92% predictive accuracy.

Dashboard Development

An interactive Power BI dashboard was created to visualize recruitment performance metrics, including:

Average Time to Hire

Average Cost per Hire

Recruiter performance analysis

Department-wise hiring trends

Job role comparisons

These dashboards enable HR teams to monitor recruitment efficiency and make data-driven decisions.

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

Recruitment Stage Insights

Training and onboarding processes accounted for nearly 50% of the total recruitment timeline, highlighting a major opportunity for process optimization.

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

Based on the analysis, the following recommendations were identified:

Optimize high-delay roles by streamlining interview and approval processes.

Reduce recruitment costs by increasing internal referrals and reducing agency reliance.

Assign high-performing recruiters to complex job roles.

Implement predictive hiring strategies to anticipate recruitment demand.

Use interactive dashboards for continuous recruitment performance monitoring.

📂 Repository Structure

The project is organized in a structured format separating data, analysis notebooks, and visualization outputs.

.
├── 📄 README.md
├── 📂 data
│   └── recruitment_dataset.csv
├── 📂 notebooks
│   └── HR_Recruitment_Analysis.ipynb
├── 📂 dashboard
│   └── recruitment_dashboard.pbix
└── 📂 visualizations
    └── charts_and_graphs
📊 Dashboard Preview

Below is the Power BI dashboard visualizing recruitment insights and hiring performance.

(Add your Power BI dashboard screenshot here)

Example:

Recruitment Analytics Dashboard

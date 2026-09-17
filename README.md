Global Online Learning -- Student Performance & Engagement Analytics

📊 Project Overview

This project is a Power BI dashboard for Online Education Analytics.
It analyzes student performance, engagement, dropout risk, demographics,
and learning outcomes using an online education dataset.

The report is designed to help understand how student engagement and
demographic factors relate to academic performance, pass results, and
dropout behavior.

🎯 Objectives

Analyze overall student performance.

Measure student engagement through activity/click data.

Compare pass and dropout outcomes.

Identify student risk levels.

Analyze performance across regions and education levels.

Explore differences by gender.

Understand the relationship between engagement and final results.

Provide interactive dashboards for easier data exploration.

🛠️ Tools & Technologies

Microsoft Power BI

Power BI Data Modeling

DAX Measures

Interactive charts, cards, slicers, and decomposition trees

Online education dataset

📁 Dataset

The Power BI model uses the dataset:

online_education_db online_education_dataset

Important fields used in the report include:

Field                 Purpose

id_student          Student identifier
region              Student geographic region
gender              Gender category
highest_education   Highest education level
engagement_level    Student engagement category
performance_level   Student performance category
risk_level          Student risk category
final_result        Final academic result
dropout_flag        Dropout indicator
total_clicks        Total learning/activity clicks

📌 Key KPIs

The dashboard contains the following main measures:

Total Students

Average Score

Pass Rate

Dropout Rate

Average Clicks

These KPIs provide a quick overview of student outcomes and engagement.

📈 Dashboard Pages

1. Student Performance & Engagement Dashboard

This page provides an overall view of:

Average score

Pass rate

Dropout rate

Average clicks

Performance level

Engagement level

Final result

Visuals include KPI cards, charts, and interactive analysis.

2. Performance & Engagement Analysis

This dashboard analyzes:

Average score by final result

Average clicks by final result

Average score by engagement level

Performance-level comparisons

It helps explore how engagement and academic outcomes are connected.

3. Global Student Performance Overview

The report includes the title:

Global Online Learning - Student Performance & Engagement Overview

This page analyzes:

Average score by region

Student distribution by final result

Student distribution by engagement level

Total clicks by engagement level

Student counts by region

Decomposition analysis using risk level, education, gender, and
region

4. Risk, Dropout & Demographic Analysis

This dashboard focuses on:

Dropout rate by highest education level

Student distribution by risk level

Final results by gender

Pass rate by highest education level

Risk and demographic analysis

5. Interactive Filters

The report uses slicers/filters for interactive analysis, including:

Region

Risk level

Engagement level

Performance level

Gender

Final result

Users can select filter values to dynamically explore the dashboard.

🔍 Major Analysis Areas

Student Performance

The report evaluates average scores and performance levels across
different student groups.

Student Engagement

total_clicks and engagement_level are used to understand student
activity and engagement.

Academic Outcomes

final_result, Pass Rate, and Dropout Rate are used to analyze student
outcomes.

Demographic Analysis

The dashboard compares results using:

Region

Gender

Highest education level

Risk & Dropout Analysis

Risk levels and dropout indicators are analyzed to identify patterns
associated with student outcomes.

📊 Power BI Visualizations

The report uses multiple Power BI visual types:

KPI/Card visuals

Clustered column charts

Pie charts

Donut charts

100% stacked bar/column charts

Decomposition tree visuals

Slicers

Q&A visual

💡 Insights This Dashboard Can Help Discover

The dashboard can be used to investigate questions such as:

Which regions have different average student scores?

How does engagement level relate to average score?

How do average clicks vary by final result?

What is the distribution of students across final results?

How does dropout rate vary by education level?

How are final results distributed across genders?

Which risk levels contain the largest number of students?

How do engagement and final results interact?

How does pass rate vary across education levels?

Which combinations of risk, education, gender, and region contribute
to student populations?

🚀 How to Use

Download or clone this repository.

Open the .pbix file using Microsoft Power BI Desktop.

Navigate through the dashboard pages.

Use the slicers to filter the data.

Interact with charts and decomposition trees to explore student
patterns.

📂 Suggested Repository Structure

online-education-analytics/
│
├── README.md
├── onlineeducation.pbix
└── screenshots/
    ├── dashboard-overview.png
    ├── performance-analysis.png
    └── risk-dropout-analysis.png

🧠 Skills Demonstrated

Data visualization

Power BI dashboard development

Data analysis

KPI creation

Interactive filtering

DAX measure usage

Student performance analysis

Exploratory data analysis

Business-style reporting

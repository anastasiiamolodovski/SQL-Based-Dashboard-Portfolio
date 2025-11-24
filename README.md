📊 SQL-Based Dashboard – User Activation Analysis

This project demonstrates how SQL can be used to extract, transform, and aggregate real campaign activation data, and visualize it in a Power BI dashboard.

The dataset represents real corporate activation campaigns, including participant segmentation, automation status, and organization size.
(PDF pages 1–4) 

🗄 Data Source & Tools

Tools Used:

PostgreSQL (advanced SQL)

Power BI

DAX

Relational data modeling

Data includes:

Campaign metadata

Participants

Activation status

Organization classification

🧠 Key Insights (from dashboard)

(PDF page 2) 

Total population: 1.9M

Active population: 1.1M

Average activation rate: 59%

Company types: SMB, Middle, Enterprise

Automation segmentation: fully automated, semi-automated, manual

Monthly activation trends

Import source distribution

These insights support automation strategy, campaign optimization, and customer onboarding decisions.

🧩 SQL Logic Overview

SQL-Based Dashboard Portfolio_ …

Core SQL functionality:

Multiple joins across participants, profiles, and campaign tables

CASE logic to classify companies by population

Filtering production and live campaigns

Excluding demo / test campaigns

Aggregations via SUM(CASE WHEN …)

Grouping by campaign alias, name, and automation state

The result powers the Power BI dashboard.

📈 Dashboard

Power BI dashboard shows:

Population breakdown

Activation trends

Automation distribution

Organization type segmentation

Import file usage

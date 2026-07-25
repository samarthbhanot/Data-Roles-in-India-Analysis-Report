# Data-Roles-in-India-Analysis-Report
Detailed Analysis of 4 major data job roles in India (Data, Analyst, Data Scientist, Business Analyst, AI Engineer)
📊 India Data Roles Project
Overview
This project is an end‑to‑end data pipeline and reporting exercise focused on the Indian job market for data roles (AI Engineers, Data Analysts, Data Scientists, Business Analysts).
It demonstrates skills in data sourcing, cleaning, automation, validation, and visualization.

🔗 Data Sourcing
Pulled job postings using the Requests library and an API connection.

Skimmed ~50 pages of API results to avoid blocking while maintaining a representative sample size (~600+ entries).

Ensured minimal duplicates and balanced coverage across job roles.

🧹 Data Cleaning
Data Analyst dataset: cleaned manually using a Python script (included in repo for reproducibility).

Other three datasets (AI Engineer, Data Scientist, Business Analyst): cleaned using VS Code + GitHub Copilot, leveraging the same Python script with prompt engineering to automate repetitive tasks.

Applied manual validation at each step to ensure accuracy and consistency.

📈 Data Modeling & Reporting
Imported cleaned datasets into Power BI.

Applied Power Query for further filtering and transformations.

Created DAX measures to calculate KPIs (e.g., job counts, skill frequencies, company hiring trends).

Built interactive dashboards highlighting:

Top hiring companies

Most in‑demand skills

Job domain distribution

Hiring trends over time

Remote vs. on‑site opportunities

🛠️ Tech Stack
Python (Requests, Pandas)

VS Code + GitHub Copilot (automation & prompt engineering)

Power BI (Power Query, DAX)

✅ Key Features
Hybrid cleaning approach: manual + automated, ensuring both scalability and human oversight.

Representative sample size: ~600+ jobs across domains, minimizing bias.

Recruiter‑friendly insights: clear dashboards and PDF report summarizing trends.

End‑to‑end workflow: from API sourcing → cleaning → validation → reporting.

📄 Deliverables
Cleaned datasets and raw datasets (.xlsx) for each role.

Python script for manual cleaning (Data Analyst dataset).

Power BI report (.pbix) with dashboards and measures.

PDF summary report with recruiter‑ready insights.

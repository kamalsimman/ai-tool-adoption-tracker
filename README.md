AI Tool Adoption Tracker — Microsoft Copilot Rollout
PM + Data Analytics Portfolio Project
Project Overview
Company: FinServ Corp (fictional — created for portfolio purposes)
Project Manager: Kamala Simman Gopalakrishnan | MS Engineering Management, FSU
Tool Deployed: Microsoft Copilot (M365)
Departments: Finance | Human Resources | Operations
FinServ Corp is rolling out Microsoft Copilot across 500 employees over 16 weeks with a $120,000 budget. What makes this project stand out from a standard software rollout is its dual mandate — not only delivering the implementation on time and within budget, but measuring whether it actually worked through a real-time Power BI adoption and ROI dashboard.

"My dashboard showed Operations was at 22% adoption by Week 8, so I triggered a 1-on-1 coaching intervention that brought them to 68% by Week 12."

Key Results
KPITargetActualStatusEmployee Adoption Rate80% by Week 1298% by Week 12✅ ExceededAvg Hours Saved/Employee/Week3+ hrs27.89 hrs✅ ExceededLicense Utilization90%+ active seats98% (490/500)✅ ExceededTraining Completion100%100%✅ MetTotal Productivity ValueBreak even in 6 months$5.02M generated✅ ExceededBudget$120,000$120,000✅ On BudgetSchedule16 weeks16 weeks✅ On Schedule

What This Project Demonstrates
SkillEvidenceProject ManagementProject Charter, RACI, Risk Register, WBS, Gantt Chart, Stakeholder Register, Communication Plan, Lessons LearnedSQL + Data Analysis10 named queries across SQLite database — adoption rates, ROI, at-risk teams, feature usage, executive summaryPower BI Dashboard3-page dashboard — Adoption Tracker, Productivity Impact, ROI DashboardChange ManagementChange Resistance Heatmap identifying at-risk teams and targeted interventionsData StorytellingSynthetic dataset of 500 employees + 4,000 usage records + 1,000 survey responses

Repository Structure
ai-tool-adoption-tracker/
│
├── 01_PM_Documents/
│   ├── 01_Project_Charter.pdf + .docx
│   ├── 02_Stakeholder_Register.pdf + .docx
│   ├── 03_RACI_Matrix.pdf + .docx
│   ├── 04_Risk_Register.pdf + .docx
│   ├── 05_Communication_Plan.pdf + .docx
│   ├── 06_Lessons_Learned.pdf + .docx
│   └── 07_WBS.docx
│
├── 02_SQL_Queries/
│   ├── 01_Adoption_By_Department.png
│   ├── 02_At_Risk_Teams.png
│   ├── 03_Weekly_Adoption_Trend.png
│   ├── 04_Hours_Saved_By_Role.png
│   ├── 05_Feature_Usage_Breakdown.png
│   ├── 06_License_Utilization.png
│   ├── 07_ROI_By_Week.png
│   ├── 08_Department_ROI_Breakdown.png
│   ├── 09_Satisfaction_Trends.png
│   └── 10_Executive_Summary.png
│
├── 03_Power_BI/
│   ├── Page1_Adoption_Tracker.png
│   ├── Page2_Productivity_Impact.png
│   └── Page3_ROI_Dashboard.png
│
├── 04_Data/
│   ├── employees.csv
│   ├── usage_data.csv
│   └── survey_results.csv
│
└── 05_Gantt_Chart/
    ├── 08_Gantt_Chart.xlsx
    └── Gantt_Screenshot.png

SQL Queries — Summary
All 10 queries were written in SQLite and executed in DB Browser for SQLite across a 3-table relational database (employees, usage_data, survey_results).
#Query NameBusiness Question Answered01Adoption By DepartmentWhich department has highest Copilot adoption?02At Risk TeamsWhich role + department combinations are below 50% adoption?03Weekly Adoption TrendHow did adoption grow week by week across 12 weeks?04Hours Saved By RoleWhich role saves the most time using Copilot?05Feature Usage BreakdownWhich Copilot features are used most?06License UtilizationHow efficiently are the 500 licenses being used?07ROI By WeekAre we on track to break even on the $120K investment?08Department ROI BreakdownWhich department generates the most productivity value?09Satisfaction TrendsAre employees getting more satisfied over time?10 Executive Summary: What is the full company-wide KPI snapshot?

Power BI Dashboard — 3 Pages
Page 1 — Adoption Tracker
KPI cards for Total Employees, Active Users, and Adoption Rate. Bar chart showing adoption by department. Line chart showing weekly adoption trend. Donut chart for feature usage breakdown. Department slicer for dynamic filtering.
Page 2 — Productivity Impact
KPI cards for Average Hours Saved, Total Hours Saved, and Active Users. Bar charts for hours saved by department and by role. Line chart for satisfaction score trend over time. Department slicer.
Page 3 — ROI Dashboard
KPI cards for Total Productivity Value ($5.02M), Net ROI ($4.90M), and Total Hours Saved. Line chart for ROI trend by week. Bar chart for department ROI breakdown. Gauge chart showing license utilization (490/500). Change Resistance Heatmap showing adoption rates and resistance levels by department and role.

Change Resistance Heatmap
The differentiating artifact of this project. Built as a Power BI Matrix visual, it shows which teams are resisting Copilot adoption and maps each resistance cluster to a targeted intervention.
TeamAdoption RateResistance LevelInterventionFinance — Analysts98.7%LOWPeer champion supportFinance — Managers98.3%LOWPeer champion supportHR — Recruiters96.9%LOWTown hall and leadership messagingHR — Generalists95.6%LOWRole based training modulesOps — Team Leads100%LOW1 on 1 coaching and use case mappingOps — Coordinators96.1%LOWQuick start guide distributed

Project Phases
Week 1-2   → Phase 1: Assessment and Planning
Week 3-6   → Phase 2: Pilot Program (50 users)
Week 7-12  → Phase 3: Full Rollout (450 users)
Week 13-16 → Phase 4: Measurement and Closeout

Database: SQLite via DB Browser for SQLite
Dashboard: Microsoft Power BI Desktop
Data Generation: Mockaroo (synthetic data — 500 employees, 4,000 usage records, 1,000 survey responses)
PM Documents: Word + PDF (Project Charter, RACI, Risk Register, WBS, Gantt, Stakeholder Register, Communication Plan, Lessons Learned)
Gantt Chart: Excel


About me
Kamala Simman Gopalakrishnan
CAPM Certified | MS Engineering Management, Florida State University (May 2026)
B.E. Electronics and Communications Engineering
This project was built as a PM + Data Analytics portfolio piece targeting entry level Project Manager, Project Coordinator, and Business Analyst roles. All company names, employee data, and scenarios are fictional and created for career development purposes.

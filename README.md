# 👥 HR Attrition Analysis | Microsoft Fabric, Power BI
## Business Problem
Employee attrition is more than just a headcount metric. Understanding where and why employees are leaving and what patterns are causing higher attrition can help organizations make better and informed retention decisions.

Employee turnover creates challenges for organisations, from losing experienced talent to disrupting team productivity and increasing recruitment costs. However, **knowing the overall attrition rate alone does not explain where the problem is most prominent or what workforce patterns are associated with employee exits.**

The objective of this analysis is to investigate employee attrition across departments, job roles and key workforce characteristics to answer three questions:

- **Where is attrition concentrated?** Identify the departments and job roles experiencing higher employee exit rates.
- **Which workforce patterns are associated with attrition?** Examine factors such as overtime, job satisfaction, work-life balance and tenure.
- **Where should HR pay closer attention?** Identify employee segments that may warrant further investigation and targeted retention efforts.

The goal is to turn employee-level HR data into meaningful insights that can help HR teams better understand workforce turnover and make more informed retention decisions.

---

## Key Findings

<img width="1454" height="157" alt="image" src="https://github.com/user-attachments/assets/41e3b50a-a311-4cc3-bfc4-3d85fd27dd88" />

- **16.1% Overall Attrition**, which is higher than the industry average of 10-15%.
- **Overtime shows clear signals** with a higher attrition of 30.5% among over-timers than just 10.4% among employees not working overtime.
- Sales-Representative appeared to be **a high-risk role** with a 39.8% attrition rate making it a notable area for further investigation.
- Age, business travel and salary also showed patterns worth paying attention, with younger employees(35.8%), frequent business travellers(24.9%) and those in lower salary bands(28.6%) having significantly higher attrition.

_These findings highlight associations and patterns in the available dataset, they do not establish that any single factor caused employees to leave._

---

## Dashboard Preview
### Overview
<img width="967" height="682" alt="image" src="https://github.com/user-attachments/assets/2c042c73-4901-42f3-80f2-580511c5fa66" />

### Deep Dive
<img width="966" height="685" alt="image" src="https://github.com/user-attachments/assets/95834c05-6323-42ae-8454-e4585929bfdc" />

---

## Tools and Technologies
1. Microsoft Fabric- Data Storage and Preparation (using Lakehouse, Dataflows Gen2, Semantic Model, Report)
2. Power BI- Data modelling, DAX, interactive visualization and reporting.

---

## Business Reccomendations
1. **Review Overtime Exposure**- Overtime might be a factor causing attrition. However Further investigation by mapping overtime with role and team, and reviewing staff and workload.
2. **Support young, early-career professionals**- Establish a smooth onboarding and early career support and mentoring. Understand the retention challenges through feedback.
3. **Target High-Risk Roles**- Sales Representatives(39.4%) and Laboratory Technician(23.9%) roles need closer attention. Do these roles have higher work pressure or workload? This must be investigated with overtime and other context to get the real picture. 
4. **Investigate travel and salary patterns**- The under 3K band is at 28.6%, and frequent travellers at 24.9%. Compare these groups by role, job level and tenure before assuming pay or travel is the cause.

---

## Business Takeaway
The analysis moves beyond reporting how many employees left to highlight where attrition is concentrated and which workforce patterns warrant closer attention. It demonstrates how HR data can be translated into actionable business insights to support more informed workforce and retention decisions.

---

## Files
- Dashboard Screenshots
- Dashboard Pdf
- Insights Pdf
- Power BI File
- Readme

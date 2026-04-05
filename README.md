# HR Analytics — Employee Attrition Dashboard
> Analyzed 1,480 employee records across 38 HR attributes using Power BI to identify the key drivers of employee attrition and help HR teams make data-backed retention decisions.

---

## Problem
The company had a 16% attrition rate but no clear picture of:
- Which employee profiles were most likely to leave
- Whether overtime, salary, or job satisfaction were the real drivers
- Which departments and job roles needed urgent retention focus

This project builds an interactive Power BI dashboard that answers all three questions — segmented by department, age group, salary slab, job role, and years at company.

---

## Dataset
- **File:** `HR_Analytics.csv`
- **Size:** 1,480 employees | 38 columns
- **Key fields:** Age, Gender, Department, Job Role, Monthly Income, Salary Slab, Education Field, Overtime, Business Travel, Job Satisfaction, Marital Status, Years at Company, Attrition (Yes/No)

---

## Tools Used
`Power BI` `DAX` `Power Query` `CSV` `HR Domain Analysis`

---

## Process

1. **Data Understanding** — Explored 1,480 records across 38 HR attributes; identified target variable (Attrition: Yes/No)
2. **Data Cleaning** — Removed duplicate employee IDs, standardized age group bins, validated salary slab categories in Power Query
3. **Feature Analysis** — Examined 10+ factors influencing attrition: overtime, salary, age, tenure, department, education, travel frequency, job satisfaction
4. **DAX Measures** — Created: Attrition Count, Attrition Rate %, Active Employees, Avg Age, Avg Salary, Avg Years at Company
5. **Dashboard Design** — Built single-page interactive dashboard with department filter buttons (HR / R&D / Sales), 7 attrition breakdown visuals: by education, age group, job role, salary slab, gender, years at company, and job role matrix
6. **Insights & Recommendations** — Derived 6 actionable HR retention strategies from the data

---

## Dashboard Preview
<img width="1326" height="739" alt="HR Analytics Dashboard" src="https://github.com/user-attachments/assets/7e0ba5dd-eeec-45e8-83c3-c9359b34a52c" />


---

## Key Findings

- **16.08% overall attrition rate** — 238 of 1,480 employees left; industry benchmark is typically 10–15%
- **Overtime is the #1 attrition driver** — employees who work overtime leave at a 30.6% rate vs only 10.4% for those who don't — a 3× difference
- **42.9% of all attrition happens within the first 2 years** — 102 of 238 leavers had ≤2 years tenure, signalling an onboarding and early engagement problem
- **Sales department has the highest attrition rate at 20.7%** — compared to R&D (13.8%) and HR (19.0%)
- **Low salary is a dominant factor** — 163 of 238 leavers (68.5%) earned under ₹5K/month; average income of leavers (₹4,813) is 29% lower than those who stayed (₹6,829)
- **26–35 age group has the highest attrition count** — 116 employees (48.7% of all leavers), the most career-mobile segment
- **Life Sciences graduates leave the most** — 89 leavers (37.4%), followed by Medical (63 leavers, 26.5%)
- **Laboratory Technicians (62) and Sales Executives (58) are the top two roles by attrition count**
- **Frequent travelers leave at 24.7%** vs 7.9% for non-travelers — travel burden significantly raises attrition risk
- **47.5% of leavers had low job satisfaction (score 1 or 2)** — satisfaction is a strong early warning signal

---

## Business Recommendations

1. **Address overtime urgently** — employees on overtime are 3× more likely to leave; implement workload redistribution or compensatory benefits
2. **Fix the first-2-year drop-off** — strengthen onboarding, mentorship programs, and 6/12-month check-ins; 43% of attrition happens here
3. **Prioritize Sales department retention** — 20.7% attrition rate needs targeted intervention: clearer career paths, better incentive structures
4. **Salary review for sub-₹5K band** — 68.5% of leavers are in the lowest salary band; even incremental raises could significantly reduce attrition
5. **Create travel policies for frequent travelers** —24.7% attrition among this group suggests travel fatigue; consider hybrid or rotation policies
6. **Monitor job satisfaction scores quarterly** — nearly half of leavers had satisfaction score ≤2; early detection enables proactive intervention

---

## Project Structure
```
hr-analytics-attrition-dashboard/
├── HR_Analytics.csv         # Raw employee dataset (1,480 rows, 38 columns)
├── HR_Dashboard.pbix        # Power BI report file
├── dashboard.png            # Dashboard screenshot
└── README.md                # This file
```

---

## Author
**Vijay Nirmalakar**
[[LinkedIn Profile](https://www.linkedin.com/in/vijaynirmalakar/)] | [[GitHub Profile](https://github.com/vijaynirmalakar)]

*Tools: Power BI | DAX | Power Query | Domain: HR Analytics, People Analytics, Attrition Modelling*

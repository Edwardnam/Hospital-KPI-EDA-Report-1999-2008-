Project Background
As a Data Analyst, I developed a high-level KPI and exploratory data analysis (EDA) dashboard using the Diabetes 130-US Hospitals dataset, which spans ten years of clinical care (1999–2008) across 130 hospitals and integrated delivery networks in the United States. The dataset includes 101,766 patient encounters diagnosed with diabetes, with each record containing demographics, admission type, discharge disposition, lab results, medications, and readmission outcomes.
The goal of this analysis was to uncover patterns in admissions, readmissions, stay durations, and insurance coverage to support hospital decision-making. This problem is critical because inadequate diabetes management in hospital settings leads to higher costs, increased readmission rates, and worsened morbidity and mortality among patients.
Executive Summary
This analysis provides a comprehensive view of hospital operations and patient outcomes for diabetic patients. Results show that emergency admissions make up the largest share of encounters, while 40% of patients are uninsured, creating financial strain and healthcare access challenges. Readmission rates peak among seniors (60–80 years), with readmitted patients consistently showing longer lengths of stay and higher treatment intensity.
These insights highlight opportunities for hospitals to improve care coordination, discharge planning, and insurance coverage, while reducing preventable readmissions and optimizing patient throughput.
Insights Deep-Dive
Patient Admissions & Readmissions
Emergency admissions dominate at ~35% of encounters, showing high reliance on acute care.
14% of patients are readmitted within 30 days, with the highest share coming from seniors (60–80 years).
Younger patients (0–40) show the lowest readmission rates, while older adults drive the majority of repeat visits.
➡️ Hospitals must prioritize diabetes management and discharge planning for seniors to reduce avoidable readmissions.
Length of Stay
The average hospital stay is ~4.5 days, but readmitted patients consistently show longer durations.
Trauma-related admissions average ~5 days, the longest of all groups, while newborn cases average just 2–3 days.
➡️ Monitoring patients with extended stays may provide early warning signals for readmission risk.
Insurance Coverage
40% of encounters are uninsured, the largest single group in the dataset.
Medicare covers 32%, while Medicaid covers ~5%.
Private insurers (Blue Cross, Aetna, Humana, etc.) each contribute only 3–4%.
➡️ The high uninsured burden highlights equity concerns and the need for expanded coverage programs.
Admission Type Distribution
Emergency admissions = 35%, Elective = 26%, Urgent = 25%.
Other/Unknown = 14%, suggesting data gaps in intake or documentation.
Newborn (0.01%) and Trauma Center (0.03%) are negligible.
➡️ Hospitals must maintain strong emergency capacity while improving data quality for admissions tracking.
Recommendations
Expand Insurance Coverage – Target the uninsured population (~40%) to reduce financial burden and ensure equitable access.
Prioritize Senior Diabetes Care – Focus interventions on the 60–80 age group, where readmission rates are highest.
Improve Emergency Care Capacity – Given that emergency cases dominate, streamline triage and outpatient referral pathways.
Leverage LOS Analytics – Use extended stay duration as an early indicator of readmission risk.
Strengthen Data Quality – Reduce reliance on “Other/Unknown” admission categories to improve reporting accuracy.
Key Questions for Stakeholders
Should readmissions be measured strictly within 30 days, or also include 60–90 days for chronic diabetic patients?
Do readmissions need to be linked to the same medical condition as the prior visit, or any cause?
How should multiple entries within 24 hours be treated (new encounter vs continuation of prior stay)?
What role can preventive diabetes management programs play in reducing hospital dependence?
Assumptions & Caveats
Readmission is measured at a 30-day interval.
Dataset is synthetic but based on real hospital patterns across 130 US institutions.
Cost data was not included; analysis instead used stay durations, readmissions, and insurance coverage as proxies for financial and operational impact.
Small categories (Newborn, Trauma) may not generalize due to limited cases.
General Info
For more about my projects and data journey, visit my Portfolio.

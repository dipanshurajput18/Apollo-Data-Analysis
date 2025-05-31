# 🏥 Apollo Hospitals: Data Analytics Dashboard
A Power BI-driven healthcare analytics project designed to extract critical insights from Apollo Hospitals' operational data. The dashboard empowers healthcare administrators and decision-makers to explore diagnosis trends, track billing-insurance gaps, monitor bed occupancy patterns, and analyze patient-doctor engagement.

# 🎯 Objectives
- Detect top diagnoses by frequency and financial impact.
- Compare billed amounts against health insurance coverage.
- Visualize hospital bed usage across Private, General, and ICU categories.
- Track the full patient journey: admission, discharge, and follow-up.
- Measure feedback volume distribution across doctors.

# 📂 Dataset Overview
## Source: Apollo Hospitals (Anonymized Internal Dataset)

## File Type: Excel Workbook

## Sheet Used: Sheet1

## Fields Included:

Patient_ID, Admit Date, Discharge Date, Follow Up Date

Diagnosis Type, Bed_Occupancy

Billing Amount, Health Insurance Amount

Doctor Name, Feedback Volume

# 🔍 Key Insights from the Dashboard
## 🧪 Diagnosis & Financial Trends
- Top Conditions: Viral Infection (2K+), Flu (1.7K+), Malaria (1.4K+)
- High Revenue Diagnoses: Viral infections and Flu top the billing and insurance charts.
- Insurance Gap: Health insurance payouts consistently fall short of billed amounts across all diagnosis types.

## 🛏️ Bed Occupancy Patterns
- Most Used: Private beds lead in occupancy (~3.5K).
- Moderately Used: General beds follow (~2.5K).
- Least Used: ICU beds (~1.2K), indicating potential overcapacity or reserved critical care resources.

## 👨‍⚕️ Feedback Analysis
- All doctors received uniform feedback volumes (1.02K), suggesting:
- A controlled patient distribution model, or
- A limitation in how feedback is currently gathered or recorded.

## 💡 Recommendations
### Optimize Resource Allocation:
- Expand Private and General bed capacity to meet patient demand.
- Re-evaluate ICU bed allocation based on real-time need.

### Review Insurance Strategies:
- Renegotiate coverage plans for high-burden diseases (e.g., Viral Infections, Malaria).
- Flag underinsured treatments for special attention.

### Enhance Feedback Systems:
- Investigate potential data normalization or collection issues in feedback volume.
- Enrich feedback metrics with sentiment or rating scores.

### Forecast Seasonal Demand:
- Use high-frequency diagnosis trends for preparing supplies, staff schedules, and ward readiness (e.g., for Flu or Viral outbreaks).

# 📊 Dashboard Features
## 🌐 Global Overview
### Offers a hospital-wide perspective on:
- Bed usage by category
- Diagnosis trends and patient counts
- Billed vs. insured amounts by disease
- Doctor-wise feedback volumes
- Time sliders for patient flow timelines

![My Image](Images/Dashboard-Apollo.png)


## 👤 Individual Patient View
### Selecting a Patient_ID reveals:
- Admission, discharge, and follow-up dates
- Diagnosis and bed occupancy details
- Specific billing and insurance coverage amounts
- Linked doctor and feedback volume

# ✅ Tools & Technologies
- Power BI – Dashboard creation, visuals, DAX-based metrics
- Microsoft Excel – Raw data source
- Power Query – Data cleansing and shaping
- DAX – Custom calculations and conditional formatting

# 🧾 Conclusion
This project showcases how hospital operational data can be transformed into powerful visual insights using Power BI. The dashboard offers both macro-level analytics and individual patient views, making it an effective decision-support tool for hospital executives, finance teams, and operations managers alike.


# U.S. Healthcare Analytics (2019–2020) — Power BI

End-to-end analytics project exploring U.S. healthcare patterns across **2019–2020**.  
Built by **Mohammed Atif Syed Ali** to turn raw, multi-source data into actionable insights for operations, finance, and outcomes.
 
> **Dataset:** De-identified, aggregated healthcare utilization & spend (2019–2020)

---
<img width="2924" height="1792" alt="Screenshot 2025-09-16 at 13 35 52" src="https://github.com/user-attachments/assets/14e4ea13-5ed3-4b84-a15b-daf3ab4f8f6a" />

## 📌 What’s Inside
- **Executive Summary:** High-level KPIs for cost, utilization, and outcomes  
- **Hospital Insights:** Admissions, discharge rates, throughput, and efficiency ratios  
- **Patient Outcomes:** Demographics & lifestyle attributes vs. outcome measures  
- **Provider & Payer Metrics:** Mix, volumes, CPT units, reimbursement trends  
- **Expense Trends:** Gross vs. adjusted spend, monthly deltas, cost optimization cues  
- **ERD & Data Model:** Clean star schema for scalable reporting

---

## 🧭 Why This Project
Healthcare data is wide, messy, and siloed. This project shows how to:
1. **Standardize & validate** inputs for trustworthy reporting  
2. **Model relationships** (patients, hospitals, payers, procedures) for flexible analysis  
3. **Operationalize insights** via interactive visuals and DAX measures that decision-makers can use

---

## 🔎 Key Questions Answered
- How did **utilization** and **expenses** shift from 2019 to 2020?  
- Which hospitals show **efficiency gaps** (e.g., AR/IPTP ratios, length-of-stay patterns)?  
- How do **payer mixes** (Medicare/Medicaid/commercial) affect volume and margin?  
- Which lifestyle or demographic factors correlate with **outcomes**?  
- Where can we **optimize cost** without degrading quality or access?




---

## 📊 Headline Metrics & Insights (Examples)
- **Utilization dip in 2020** consistent with service deferrals; elective volumes lagged recovery.  
- **Payer concentration risk:** Medicare + commercial dominate CPT units; small shifts move revenue materially.  
- **Efficiency dispersion** across hospitals visible in AR/IPTP ratios; targeted process work can close gaps.  
- **Lifestyle factors** (exercise, diet, tobacco) align with outcome variability; prevention lever is meaningful.  
- **Expense seasonality:** Peaks tied to service utilization & supply cycles; procurement timing can reduce spend.

<img width="2924" height="1778" alt="Screenshot 2025-09-16 at 13 36 03" src="https://github.com/user-attachments/assets/f14a3611-39a0-4bc9-a809-584859e310a3" />
<img width="2892" height="1760" alt="Screenshot 2025-09-16 at 13 36 30" src="https://github.com/user-attachments/assets/e6eb7473-f909-4743-ba12-75eaaa337eb5" />
<img width="2798" height="1758" alt="Screenshot 2025-09-16 at 13 37 04" src="https://github.com/user-attachments/assets/d2e1fb9a-54bc-4cc1-b05a-e75bed90545f" />




---

## 🧱 Data Model (Star Schema)
- **Facts:** Encounters/claims, procedures (CPT), expenses (monthly)  
- **Dimensions:** Date, Hospital, Provider, Payer, Patient (de-identified), Geography, Procedure  
- **Grain:** Hourly/daily encounters rolled to monthly where appropriate  
- **Governance:** Type consistency, de-duplication, cross-table key validation

<img width="2934" height="1508" alt="Screenshot 2025-09-16 at 13 37 14" src="https://github.com/user-attachments/assets/49c6afb3-5eb0-4839-8bba-9f332998c2cf" />




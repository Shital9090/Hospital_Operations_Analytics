# 🏥 MediPulse – Hospital Management & Analytics Dashboard 🏥

**End-to-End Healthcare BI Solution**  
**Power BI | 10,000 Patients | 2024–2025 Data** | Real-World Hospital Insights

![](https://i0.wp.com/thedeveloperyt.com/wp-content/uploads/2025/05/Hospital_Dashboard-2_page-0001.jpg?fit=2075%2C1200&ssl=1)
*(Add your best combined screenshot or collage here)*

## Project Overview

**Project Name:** MediPulse – Comprehensive Hospital Operations & Patient Analytics Dashboard

**Domain:** Healthcare Analytics | Hospital Management | Business Intelligence

**Tools Used:**  
- Power BI Desktop  
- DAX for advanced measures  
- Power Query for data transformation & modeling

**Dataset Highlights**  
- 10,000 Patient Records  
- 10,000 Appointments  
- 10,000 Doctors (likely anonymized IDs)  
- Total Revenue: ₹49 Million  
- Time Period: 2024–2025  
- Key Entities: Patients, Appointments, Doctors, Resources (Beds, Ventilators, CT Scan, MRI, ECG), Diseases, Cities, Departments (ICU, Emergency, OPD, Surgery, Radiology)

**Business Goals**  
- Monitor hospital revenue, appointment trends & payment behavior  
- Optimize resource utilization (beds, ventilators, imaging equipment)  
- Understand patient demographics, disease patterns & geographic distribution  
- Evaluate doctor performance, patient stay duration & hospital efficiency  
- Provide actionable insights for hospital administrators, finance teams & clinical managers

## Dashboard Breakdown

### 1. Appointments, Billing & Payments Dashboard
**Focus:** Revenue generation, appointment types, payment status & collection efficiency

![](https://github.com/Shital9090/Hospital_Operations_Analytics/blob/main/Power%20bi%20Unguided/Screenshot%202026-01-04%20213731.png)

**Key Metrics**  
- Total Appointments: 10,000  
- Total Revenue: ₹49 Million

**Main Visuals**  
- Sum of Total Amount by Year & Month (Line Chart) – Monthly revenue trend in 2025  
- Sum of Consultation Fee + Test Cost + Medicine Cost by Appointment Type (Stacked Bar)  
- Count of Appointments by Payment Status (Pie Chart) – ~50% Paid | ~50% Pending  
- Sum of Total Amount by Payment Mode (Bar Chart) – Cash, Insurance, UPI, Card

**Core Insights**  
- Revenue shows steady growth with minor fluctuations throughout 2025  
- OPD & Emergency contribute significantly to consultation & test revenue  
- Nearly 50% of payments are still pending → opportunity to improve follow-up & digital collection (UPI/Card)

### 2. Resource Utilization Dashboard
**Focus:** Bed, equipment & department-wise occupancy & availability

![](https://github.com/Shital9090/Hospital_Operations_Analytics/blob/main/Power%20bi%20Unguided/Screenshot%202026-01-04%20213710.png)
**Key Metrics**  
- Total Resources Tracked: 300+ (69 Beds, 64 CT Scans, 54 ECGs, 59 Ventilators, 54 MRIs)  
- Occupied Resources: 156

**Main Visuals**  
- Count of Resources by Type & Availability (Stacked Bar)  
- Count of Resources by Department (Bar Chart) – ICU highest (106 beds/scans/etc.)  
- Donut Chart: Resource Type Distribution  
- Table: Department-wise Bed/Scan/ECG/MRI/Ventilator counts

**Core Insights**  
- ICU & Emergency departments have highest resource load  
- Beds & Ventilators show significant occupancy → capacity planning needed  
- CT Scan & MRI utilization is balanced but high in Radiology

### 3. Patient Admission & Disease Analysis Dashboard
**Focus:** Disease prevalence, gender & city-wise patient distribution

![](https://github.com/Shital9090/Hospital_Operations_Analytics/blob/main/Power%20bi%20Unguided/Screenshot%202026-01-04%20213616.png)
**Key Metrics**  
- Total Patients: 10,000  
- Average Patient Age: 45.69 years

**Main Visuals**  
- Count of Patients by Disease (Bar Chart) – Asthma, Heart Disease, Fracture, Cancer, Diabetes, Covid-19 leading  
- Count of Patients by City (Bar Chart) – Delhi highest (~1.74K), followed by Mumbai, Chennai, etc.  
- Stacked Bar: Disease & Gender distribution  
- Gender Split: 50.21% Male | 49.79% Female

**Core Insights**  
- Respiratory (Asthma), Cardiovascular (Heart Disease) & Lifestyle diseases (Diabetes) dominate  
- Metro cities (Delhi, Mumbai, Chennai) contribute most admissions  
- Gender distribution nearly equal across major diseases

### 4. Geographic & Patient Distribution Dashboard
**Focus:** City-level patient load, gender & disease breakdown

![](https://github.com/Shital9090/Hospital_Operations_Analytics/blob/main/Power%20bi%20Unguided/Screenshot%202026-01-04%20213819.png)
**Main Visuals**  
- Count of Patients by City (Bar Chart)  
- Stacked Bar: Disease distribution by City  
- Donut Chart: Gender by City  
- Table: City × Disease matrix with totals

**Core Insights**  
- Delhi, Mumbai, Chennai, Hyderabad, Pune, Bangalore — almost even patient load  
- Asthma & Heart Disease consistently high across all cities

### 5. Patient Stay & Hospital Efficiency Dashboard
**Focus:** Length of Stay (LOS), billing & yearly admission trends

![](https://github.com/Shital9090/Hospital_Operations_Analytics/blob/main/Power%20bi%20Unguided/Screenshot%202026-01-04%20213754.png)
**Key Metrics**  
- Total Length of Stay (Sum): 106K–213K days (across visuals)  
- Average LOS varies by disease (5–10 days)

**Main Visuals**  
- Average Length of Stay by Disease (Bar Chart)  
- Sum of Length of Stay (Gauge / KPI)  
- Patient Count by Year (Line Chart) – Growth from 2024 to 2025  
- Table: Sample patient-level LOS & billing

**Core Insights**  
- Fracture, Heart Disease & Covid-19 show longer average stays  
- Strong patient admission growth in 2025 → hospital scaling successfully

### 6. Hospital Overview Dashboard
**Focus:** High-level KPIs & demographic summaries

![](https://github.com/Shital9090/Hospital_Operations_Analytics/blob/main/Power%20bi%20Unguided/Screenshot%202026-01-04%20194418.png)

**Key Metrics**  
- Patients: 10K | Appointments: 10K | Doctors: 10K | Revenue: ₹49M

**Main Visuals**  
- Gender distribution (Donut)  
- Doctors by City (Bar)  
- Patients by Year & Month (Line)

### 7. Doctor Performance Dashboard
**Focus:** Doctor-wise patient load, stay duration & experience

![](https://github.com/Shital9090/Hospital_Operations_Analytics/blob/main/Power%20bi%20Unguided/Screenshot%202026-01-04%20213643.png)
**Key Metrics**  
- Avg Length of Stay (overall): 10.64 days  
- Avg Experience: 20.76 years

**Main Visuals**  
- Count of Patients by Doctor Name (Bar Chart)  
- Table: Doctor × Department × LOS × Patients  
- Scatter/Bubble: Experience vs Patient Load vs LOS

**Core Insights**  
- High patient load on certain doctors (Doctor_1 appears heavily in Emergency)  
- Opportunity to balance workload & monitor burnout risk

## How to Use
1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Use slicers: Appointment Type, Payment Status, Disease, City, Department, Doctor, Year  
4. Cross-filter & drill-down across pages

## Future Enhancements
- Doctor efficiency score (patients/day, revenue/doctor)  
- Readmission rate analysis  
- Predictive bed occupancy forecasting  
- Publish to Power BI Service + mobile layout

Made with passion for healthcare analytics in Sholapur, Maharashtra 🩺📊  
Shital | Data Analytics Enthusiast

Feel free to ⭐ the repo or fork it!

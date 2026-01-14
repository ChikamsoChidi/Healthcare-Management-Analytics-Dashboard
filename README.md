# Healthcare Management and Analytics Dashboard

## Project Overview
This project features a comprehensive business intelligence solution developed for Asclepius Health. The dashboard provides stakeholders with real-time visibility into financial performance, patient throughput, clinical efficiency, and doctor productivity. 

The current documentation reflects the analysis of Central Hospital, one of three hospital branches integrated into the centralized reporting system.

## Technical Stack
* Data Visualization: Power BI
* Data Modeling: Star Schema with centralized Fact tables for Transactions and Appointments
* Dynamic Filtering: Implementation of global slicers for Hospital Branch and Date Ranges
* Key Metrics: Calculated Fields used for Revenue Leakage and Appointment Completion Rates

## Analysis and Insights

### 1. Financial Operations and Revenue Cycle
![Financial Dashboard](images/financials.png)
This section tracks the financial health of the facility, specifically focusing on the status of transaction processing.
* Total Revenue: The hospital generated $86,460.11 in paid revenue, though the broader system shows over $229,000 in total billed services.
* Payment Diversification: Revenue is evenly split between Insurance (34.52%), Credit Card (33.33%), and Cash (32.14%).
* Revenue Leakage: A significant portion of revenue ($82,369.67) is categorized as Failed, indicating a need for improved billing verification processes.

### 2. Clinical Productivity and Specializations
![Doctor Performance](images/doctors.png)
This module analyzes practitioner performance and the profitability of specific medical departments.
* Top Performers: Dr. Sarah Taylor (Dermatology) is the highest-earning practitioner, contributing $33.8K in annual earnings.
* Departmental Revenue: Pediatrics is the highest revenue-generating specialization, totaling $52.6K.
* Treatment Utilization: X-Ray services represent the highest treatment-specific revenue at $33.7K.

### 3. Patient Demographics and Appointment Integrity
![Patient Analytics](images/patients.png)
This module monitors patient flow and the reliability of scheduled appointments.
* Patient Density: The highest concentration of patients falls within the 25 to 35 age demographic.
* Volume Trends: Patient registration saw a significant peak in late 2021 followed by a stabilization period throughout 2022 and 2023.
* Attrition Analysis: There were 26 no-shows and 19 cancellations compared to 15 completed visits, suggesting a need for a more robust appointment reminder system.

### 4. Treatment Cost and Efficiency Analysis
![Treatment Costs](images/treatments.png)
This section breaks down the average costs associated with different medical protocols.
* Cost Variance: MRI and X-Ray Basic Screening protocols are the most expensive standard procedures, both averaging approximately $4.0K.
* Operational Completion: MRI and Physiotherapy show the highest rates of No-show status (38% and 38% respectively), which negatively impacts the utilization of expensive medical equipment.

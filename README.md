# Sales New Account Onboarding Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analysis-1F6FEB)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Preparation-217346)
![Portfolio Project](https://img.shields.io/badge/Project-Portfolio%20Project-success)

## 📊 Project Overview

The **Sales New Account Onboarding Dashboard** is a Power BI business intelligence solution designed to provide visibility into the new account onboarding lifecycle—from initial request submission through credit review, customer documentation, account creation, and account activation.

The dashboard combines executive-level KPIs with operational detail to help answer a practical business question:

> **Where are new account opportunities progressing successfully, where are they getting delayed, and what factors are contributing to lost opportunities?**

This project uses a **synthetic dataset of 25 account onboarding records** created for portfolio demonstration.

---

## 🎯 Business Problem

Sales new-account onboarding involves multiple process steps, customer interactions, and internal handoffs.

Without a centralized view, teams may have difficulty identifying:

- Where accounts are currently positioned in the onboarding process
- Which accounts require follow-up
- Where onboarding time is accumulating
- What documentation or setup issues are causing delays
- Why opportunities are being lost

This dashboard was developed to provide a centralized view of the onboarding process and support data-driven operational and process-improvement decisions.

---

# 📈 Dashboard Overview

## 01 — Executive Dashboard

The Executive Dashboard provides a high-level view of onboarding pipeline health.

### Key Metrics

- **25** New Account Opportunities
- **5** Active Accounts
- **16** Pending Requests
- **4** Lost Opportunities

The dashboard also provides filtering by:

- Month/Year
- Pipeline Status
- Sales Team Assignee

![Executive Dashboard](https://github.com/user-attachments/assets/10c57628-cfb8-424c-bbcf-b58849262b62)

---

## 02 — Onboarding Milestones

The Onboarding Milestones page tracks the progression of accounts through key onboarding activities.

### Milestones Analyzed

- DocuSign packet sent
- Customer reminder
- DocuSign received
- Application forwarded to Credit
- Account creation
- Welcome package
- Account activation
- Elapsed onboarding time

![Onboarding Milestones](https://github.com/user-attachments/assets/2cddaecc-81d2-4507-9e75-4eb84b80f82c)

---

## 03 — Opportunity Roadblocks

The Opportunity Roadblocks page focuses on the operational issues that can delay or prevent account completion.

### Roadblock Categories

- Credit Review
- Customer Engagement
- Documentation
- Legal / Compliance
- Project Change / Cancellation
- Tax / Regulatory

The detailed pipeline view connects roadblock categories to individual account setup issues.

![Opportunity Roadblocks](https://github.com/user-attachments/assets/c2fbf573-99d3-4577-b104-58b10cbaca15)

---

## 04 — Data Export

The Data Export page provides an account-level operational view of the underlying onboarding records.

This allows users to review detailed account information and export data for additional analysis or operational follow-up.

![Data Export](https://github.com/user-attachments/assets/3c7d40cf-e2f0-4a39-9985-4d7beb4b3a28)

---

# 🔄 Onboarding Process

The dashboard follows the account onboarding workflow:

```text
Request Submitted
        ↓
Credit Review
        ↓
Awaiting Customer Documents
        ↓
Account Created
        ↓
Welcome Package Sent
        ↓
Account Active / Ready for Order

---

#  📌 Dataset Snapshot
The portfolio dataset contains 25 synthetic records.
Status	Records
Request Submitted	4
Credit Review in Progress	6
Awaiting Customer Documents	6
Account Active	5
Opportunity Lost	4
Total	25

Account Type	Records
Acquisition	14
New Account	11
The data is fictional/synthetic and does not contain real customer information.
---

#  🔎 Analytical Approach
The project focuses on four areas:
Pipeline Visibility
The Executive Dashboard shows where each opportunity currently sits in the onboarding workflow and provides filters for time period, status, and sales team assignee.
Onboarding Efficiency
Milestone dates are used to examine elapsed time between key activities and identify where time accumulates during the onboarding process.
Bottleneck Analysis
Roadblock categories and account-level setup issues are analyzed to identify recurring operational barriers such as documentation, customer engagement, credit, legal/compliance, and tax/regulatory requirements.
Opportunity Loss
Lost opportunities are separated from active work in progress so that pending accounts are not incorrectly interpreted as failed conversions. The dashboard provides visibility into the reasons associated with lost opportunities.

---
#  💡 Business Value
A dashboard of this type can support sales and onboarding teams by helping them:
Prioritize accounts requiring follow-up.
Identify recurring documentation or setup issues.
Monitor onboarding cycle time.
Surface process bottlenecks.
Distinguish active work from lost opportunities.
Identify areas where process improvements may reduce delays.
---

# 🛠️ Tools & Technologies
Microsoft Power BI — Interactive dashboard development
DAX — Measures, KPIs, and elapsed-time calculations
Power Query — Data preparation and transformation
Microsoft Excel — Synthetic source dataset
Data Visualization — Executive and operational reporting
Business Process Analysis — Workflow and bottleneck analysis

---

# 📋 Key Data Fields
The source data includes fields such as:
Account Type
Status
Company
Customer Name
Account Number
Creation Date
DocuSign Packet Sent to Customer
Reminder Sent to Customer
DocuSign Received from Customer
Application Forwarded to Credit
Account Created Date
Welcome Package Sent
Assigned To
Created By
Number of Updates
Account Setup Roadblocks
Opportunity Lost Reason

---

# 📁 Repository Structure
```text
Sales-New-Account-Onboarding-Dashboard/
│
├── README.md
│
├── PowerBI/
│   └── Sales New Account Onboarding Dashboard.pbix
│
├── data/
│   └── Account Onboarding Test Data.xlsx
│
├── screenshots/
│   ├── 01_Executive_Dashboard.png
│   ├── 02_Onboarding_Milestones.png
│   ├── 03_Opportunity_Roadblocks.png
│   └── 04_Data_Export.png
│
├── documentation/
│   ├── Business_Problem.md
│   ├── KPI_Definitions.md
│   └── Process_Flow.md
│
└── DAX/
    └── Measures.md
```
#👩🏽‍💻 Skills Demonstrated
This project demonstrates skills in:
Reporting & Business Intelligence
Power BI Dashboard Development
DAX
Power Query
KPI Development
Operational Reporting
Data Visualization
Process Improvement
Workflow Analysis
Bottleneck / Root-Cause Analysis
Business Stakeholder-Oriented Reporting

---

#🔗 Related Portfolio Project
This project complements the Greenwood Clinical Admissions Analysis 2023 project by demonstrating a different business domain and a stronger operational/process-reporting focus.
---
Portfolio Project | Sales Operations & Business Intelligence

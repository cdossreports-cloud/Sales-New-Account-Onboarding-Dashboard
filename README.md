# Sales New Account Onboarding Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Analysis-1F6FEB)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Preparation-217346)
![Status](https://img.shields.io/badge/Project-Portfolio%20Ready-success)

<img width="1068" height="614" alt="01_Executive_Dashboard" src="https://github.com/user-attachments/assets/3978f266-6c9c-4f09-8467-8999072d17b5" />
<img width="1380" height="752" alt="HAG Generated_Image" src="https://github.com/user-attachments/assets/9db43d50-4bf4-4c37-afac-ebe0511fbc72" />


## 📊 Project Overview

The **Sales New Account Onboarding Dashboard** is a Power BI business intelligence project designed to provide visibility into the new account onboarding lifecycle—from initial request submission through credit review, customer documentation, account creation, and account activation.

The dashboard combines executive-level KPIs with operational detail to help answer a practical business question:

> **Where are new account opportunities progressing successfully, where are they getting delayed, and what factors are contributing to lost opportunities?**

The project uses a synthetic dataset of **25 account onboarding records** created for portfolio demonstration.

## 🎯 Business Objectives

- Monitor the health of the new account onboarding pipeline.
- Track accounts by onboarding status and milestone.
- Measure elapsed time across key onboarding activities.
- Identify recurring account setup roadblocks.
- Analyze reasons for opportunity loss.
- Provide an operational account-level view for follow-up and reporting.

# Business Problem

Sales new-account onboarding involves multiple handoffs and customer-facing milestones. Without a centralized view, teams may have difficulty identifying where accounts are waiting, which issues are recurring, and where opportunities are being lost.

This project addresses that reporting need by creating a Power BI dashboard that combines pipeline visibility, milestone tracking, cycle-time analysis, roadblock analysis, and account-level operational detail.

## Objectives

1. Provide a single view of onboarding pipeline health.
2. Identify accounts requiring follow-up.
3. Measure elapsed time across onboarding milestones.
4. Surface recurring roadblocks.
5. Separate work in progress from lost opportunities.
6. Support process-improvement conversations with data.
## 📈 Dashboard Pages

### 1. Executive Dashboard

Provides a high-level snapshot of onboarding activity with:

- **25** New Account Opportunities
- **5** Active Accounts
- **16** Pending Requests
- **4** Lost Opportunities
- Pipeline summary by onboarding status
- Month/year filtering
- Pipeline status filtering
- Sales team assignee filtering

<img width="1068" height="614" alt="01_Executive_Dashboard" src="https://github.com/user-attachments/assets/c27320b7-681d-471e-9f9d-ec849ce12bc3" />


### 2. Onboarding Milestones

Tracks the progression of accounts through important onboarding milestones, including:

- DocuSign packet sent
- Reminder sent to customer
- DocuSign received
- Application forwarded to Credit
- Account creation
- Welcome package
- Elapsed onboarding time
  
<img width="1088" height="608" alt="02_Onboarding_Milestones" src="https://github.com/user-attachments/assets/e2306f05-00d3-49f8-8203-12fb65c7778b" />



### 3. Opportunity Roadblocks

Analyzes the operational issues that can delay or prevent account completion.

Roadblock categories represented in the dashboard include:

- Credit Review
- Customer Engagement
- Documentation
- Legal / Compliance
- Project Change / Cancellation
- Tax / Regulatory

The detailed pipeline summary connects these categories to individual accounts and specific setup issues.

<img width="1094" height="619" alt="03_Opportunity_Roadblocks" src="https://github.com/user-attachments/assets/b27d751b-5fec-40f1-9a13-d558fe29c8c2" />


### 4. Data Export

Provides a detailed account-level view of the onboarding dataset and supports operational review/export of the underlying records.

<img width="1088" height="593" alt="04_Data_Export" src="https://github.com/user-attachments/assets/a34011ab-4372-430f-95f5-c258a197c122" />


## 🔄 Onboarding Process

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
```

**Opportunity Lost** is treated as a separate outcome rather than as an active onboarding stage.

## 📌 Dataset Snapshot

The portfolio dataset contains **25 synthetic records**.

| Status | Records |
|---|---:|
| Request Submitted | 4 |
| Credit Review in Progress | 6 |
| Awaiting Customer Documents | 6 |
| Account Active | 5 |
| Opportunity Lost | 4 |
| **Total** | **25** |

| Account Type | Records |
|---|---:|
| Acquisition | 14 |
| New Account | 11 |

The data is fictional/synthetic and does not contain real customer information.

## 🔎 Analytical Approach

The project focuses on four areas:

### Pipeline Visibility

The Executive Dashboard shows where each opportunity currently sits in the onboarding workflow and provides filters for time period, status, and sales team assignee.

### Onboarding Efficiency

Milestone dates are used to examine elapsed time between key activities and identify where time accumulates during the onboarding process.

### Bottleneck Analysis

Roadblock categories and account-level setup issues are analyzed to identify recurring operational barriers such as documentation, customer engagement, credit, legal/compliance, and tax/regulatory requirements.

### Opportunity Loss

Lost opportunities are separated from active work in progress so that pending accounts are not incorrectly interpreted as failed conversions. The dashboard provides visibility into the reasons associated with lost opportunities.

## 💡 Business Value

A dashboard of this type can support sales and onboarding teams by helping them:

- Prioritize accounts requiring follow-up.
- Identify recurring documentation or setup issues.
- Monitor onboarding cycle time.
- Surface process bottlenecks.
- Distinguish active work from lost opportunities.
- Identify areas where process improvements may reduce delays.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Interactive dashboard development
- **DAX** — Measures, KPIs, and elapsed-time calculations
- **Power Query** — Data preparation and transformation
- **Microsoft Excel** — Synthetic source dataset
- **Data Visualization** — Executive and operational reporting
- **Business Process Analysis** — Workflow and bottleneck analysis

## 📋 Key Data Fields

The source data includes fields such as:

- Account Type
- Status
- Company
- Customer Name
- Account Number
- Creation Date
- DocuSign Packet Sent to Customer
- Reminder Sent to Customer
- DocuSign Received from Customer
- Application Forwarded to Credit
- Account Created Date
- Welcome Package Sent
- Assigned To
- Created By
- Number of Updates
- Account Setup Roadblocks
- Opportunity Lost Reason

## 📁 Repository Structure

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

## 👩🏽‍💻 Skills Demonstrated

This project demonstrates skills in:

- Reporting & Business Intelligence
- Power BI Dashboard Development
- DAX
- Power Query
- KPI Development
- Operational Reporting
- Data Visualization
- Process Improvement
- Workflow Analysis
- Bottleneck / Root-Cause Analysis
- Business Stakeholder-Oriented Reporting

## 🔗 Related Portfolio Project

This project complements the **Greenwood Clinical Admissions Analysis 2023** project by demonstrating a different business domain and a stronger operational/process-reporting focus.

---

**Portfolio Project | Sales Operations & Business Intelligence**

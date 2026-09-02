# Insurance data project

# 🛡️ InsureSight: Insurance Policy & Claims Analytics Dashboard
 
An interactive Power BI dashboard built to analyze insurance policies, premiums, coverage, and claims data — helping identify risk patterns, claim trends, and customer segments at a glance.
 
## 📌 Purpose
 
InsureSight is a Power BI report designed to give insurers, analysts, and business teams a clear view of policy performance and claims behavior across customer segments. It brings together premium collection, coverage exposure, claim outcomes, and customer demographics into a single, filterable view — making it easy to spot trends without digging through raw spreadsheets.
 
## 🧰 Tech Stack
 
- **📊 Power BI Desktop** – Main platform used to build the report and visuals
- **📂 Power Query** – Used to clean and shape the raw insurance data
- **🧠 DAX** – Powers the aggregated measures behind the cards, charts, and pivot table (sums, counts, etc.)
- **📝 Data Modeling** – Relationships built across the policy/claims table and date tables to support time-based filtering
- **📁 File Format** – `.pbit` (template) for development, `.png` for dashboard previews
## 🗂️ Data Source
 
*(Add details here — e.g. where the dataset came from: a public dataset, sample/synthetic data, or your own source, and roughly how many records/policies it covers.)*
 
The core dataset includes policy-level records with the following fields: Policy Number, Customer ID, Gender, Age, Age Group, Policy Type, Policy Start/End Date, Premium Amount, Coverage Amount, Claim Number, Claim Date, Claim Amount, Claim Status, and Active/Inactive status.
 
## ✨ Features / Highlights
 
### Business Problem
Insurance teams handle large volumes of policy and claims data, but it's often hard to quickly answer questions like:
- Which policy types generate the most premium revenue?
- How do claim amounts vary across age groups?
- What's the approval/rejection breakdown of claims?
- How many customers are active vs. inactive?
These questions are slow to answer from raw tables alone.
 
### Goal of the Dashboard
To provide a single interactive view that:
- Summarizes total premiums, coverage, and claims at a glance
- Lets users filter by Policy Number, Claim Number, or Customer ID
- Breaks down claims and premiums by policy type, age group, and status
- Supports drill-down into individual customer/policy records
### Walkthrough of Key Visuals
 
**KPI Cards (Top)**
- Total Premium Amount
- Total Coverage Amount
- Total Claim Amount
**Slicers (Filters)**
- Filter the entire report by Policy Number, Claim Number, or Customer ID
**Gender Breakdown (Multi-Row Card)**
- Count of customers by gender
**Claim Status Ribbon Chart**
- Visualizes the distribution and trend of claims across statuses (e.g. Approved, Pending, Rejected)
**Premium by Policy Type (Bar Chart)**
- Ranks policy types by total premium collected, highlighting the most profitable policy categories
**Claim Amount by Age Group (Line Chart)**
- Shows how total claim amounts trend across different age groups, useful for risk profiling
**Active vs. Inactive Customers (Donut Chart)**
- Quick visual split of active vs. inactive policyholders
**Coverage by Policy Type & Claim Status (Pivot Table)**
- Cross-tabulates total coverage amount by policy type (rows) and claim status (columns) for detailed analysis
**Detailed Records Table (Page 2)**
- A full record-level table with Policy Number, Customer ID, Claim Number, Age, Gender, Coverage Amount, Premium Amount, Policy Dates, Policy Type, and Claim Status for row-level investigation
### Business Impact & Insights
- **Risk Assessment**: Identify which age groups or policy types are associated with higher claim amounts
- **Revenue Analysis**: See which policy types drive the most premium income
- **Customer Retention**: Track active vs. inactive policyholders to flag churn risk
- **Claims Efficiency**: Monitor the spread of claim statuses to spot bottlenecks in approvals
## 📸 Screenshots / Demo
 <img width="1418" height="752" alt="Screenshot 2026-09-02 113048" src="https://github.com/user-attachments/assets/1600d0e5-2ae1-4f2b-95dd-5f4c6c7d3eee" />



# Credit Card Consumer Complaints Analysis

## Project Overview

This project analyzes credit card consumer complaints from the **Consumer Financial Protection Bureau (CFPB) Consumer Complaint Database**.

The goal was to identify the main complaint issues, companies and states with the highest complaint volume, complaint trends over time, and company response performance.

The project was completed in Microsoft Excel using Power Query, the Excel Data Model, PivotTables, PivotCharts, slicers, a Timeline, and dynamic KPI cards.

---

## Data Source

Source: Consumer Financial Protection Bureau (CFPB) Consumer Complaint Database

Official dataset:  
https://www.consumerfinance.gov/data-research/consumer-complaints/

For this project, the dataset was filtered to:

- Product: Credit card
- Date range: October 2025 to October 2026

### Project Files

- [Interactive Excel Workbook] https://docs.google.com/spreadsheets/d/1OqX55stIbl_oSMHUm6q1Rs0v4o5HOYFf/edit?usp=drive_link&ouid=113029233647282482553&rtpof=true&sd=true
- [Raw CFPB Data Used for This Project] https://drive.google.com/file/d/1bOd82eBP--E7AWVuMIMfsiuU5S-A4KSh/view?usp=sharing

---

## Dataset Summary

The cleaned dataset contains:

- 93,469 complaints
- 548 distinct companies
- 15 complaint issue categories
- Multiple U.S. states and territories
- Multiple company response types
- Multiple submission channels

---

## Business Questions

1. What are the most common complaint issues?
2. Which companies receive the most complaints?
3. Which states have the highest complaint volume?
4. How does complaint volume change over time?
5. What types of responses do companies provide to consumers?
6. Which submission channels are used most frequently?
7. What percentage of complaints receive a timely response?
8. Which high-volume companies show weaker timely-response performance?

---

## Tools Used

- Microsoft Excel
- Power Query
- Excel Data Model
- PivotTables
- PivotCharts
- Distinct Count
- Slicers
- Timeline
- Combo Charts
- Secondary Axis
- Data Cleaning
- Data Validation
- Dashboard Design

---

## Key KPIs

| KPI | Value |
|---|---:|
| Total Complaints | 93,469 |
| Total Companies | 548 |
| Timely Responses | 92,335 |
| Untimely Responses | 1,134 |
| Timely Response Rate | 98.79% |

The KPI values were built from PivotTables and connected to dashboard filters so they can update dynamically.

---

## Key Insights

- Purchase-related statement problems were the leading complaint issue, with 30,190 complaints.
- Capital One Financial Corporation had the highest complaint volume, with 13,366 complaints.
- California recorded the highest complaint volume by state, with 14,700 complaints.
- Web was the dominant submission channel, with 86,127 complaints.
- Overall timely-response performance was 98.79%.
- Synchrony Financial showed weaker timely-response performance among the highest-volume companies.

Complaint volume should not automatically be interpreted as company performance because larger companies may have more customers.

---

## Dashboard Features

The interactive Excel dashboard includes:

- Dynamic KPI cards
- Top 5 complaint issues
- Top 5 companies by complaint volume
- Top 5 states by complaint volume
- Complaint trend over time
- Company response analysis
- Submission channel analysis
- Timely response analysis
- High-volume companies vs timely-response performance

### Interactive Filters

The dashboard can be filtered by:

- Company
- State
- Issue
- Submitted Via
- Timely Response
- Date Received

---

## Dashboard Preview

![Credit Card Consumer Complaints Dashboard](images/credit_card_complaints_dashboard.png)

---

## Important Excel Technique Learned

One of the most valuable techniques used in this project was calculating unique values in a PivotTable.

To use Distinct Count:

1. Insert a PivotTable
2. Select **Add this data to the Data Model**
3. Add the field to the Values area
4. Open **Value Field Settings**
5. Select **Distinct Count**

For this project:

> Distinct Count of Company = 548

This allowed the Total Companies KPI to remain dynamic and respond to dashboard filters.

---

## What I Learned

This project helped strengthen my skills in:

- cleaning and validating data with Power Query
- using the Excel Data Model
- calculating distinct values in PivotTables
- creating dynamic KPIs
- connecting multiple PivotTables to shared slicers
- using a Timeline for date filtering
- building PivotCharts
- creating combo charts with secondary axes
- designing interactive dashboards
- translating analytical results into business insights

A major learning from this project was:

> For a distinct count in a PivotTable, add the source data to the Data Model, then use Value Field Settings → Distinct Count.

---

## Repository Structure

credit-card-consumer-complaints-analysis/
│
├── README.md
└── images/
    └── credit_card_complaints_dashboard.png
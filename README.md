# Credit Card Customer Complaint Performance Dashboard
The Credit Card Customer Complaint Performance Dashboard is an interactive Excel dashboard designed to analyze customer complaints from 2023 to 2025.
The dashboard provides insights into complaint trends, company performance, response efficiency, and complaint resolution outcomes. It enables users to filter data dynamically by year, company, and issue to explore patterns and performance changes.



![alt text](<CREDIT CARD COMPLAINT DASHBOARD. ori PNG.PNG>)



## Objectives
This project aims to:
- Analyze total complaint volume across multiple years
- Evaluate timely response performance
- Assess monetary relief distribution
- Identify the most common complaint issues
- Compare company-level complaint performance
- Monitor complaint trends over time
--- 

## Key Performance Indicators (KPIs)
The dashboard tracks the following KPIs:
- Total Complaints
- Year-over-Year (YoY) Change in Complaints
- Timely Response Rate (%)
- Monetary Relief Rate (%)
- Top Complaint Issue

All KPIs are dynamic and update automatically based on slicer selections.

## Tools and Skills Used
 ### Microsoft Excel

Core Excel Features:

- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- Logical Function (IF Function)
- GETPIVOTDATA
- KPI Card Development
- Dashboard Layout Design
### Data Transformation – Power Query
Power Query was used to clean and structure the raw dataset before analysis.

### Dataset Overview
columns:

Date received, Product, Sub-product,	Issue,	Sub-issue,	Consumer complaint narrative,	Company public response,	Company,	State,	ZIP code,	  Tags,	Consumer consent provided?, Submitted via,	Date sent to company,	Company response to consumer,	Timely response?,	Consumer disputed?,	Complaint ID

### Sample Preview 
<img width="1193" height="521" alt="COMPLAINTS VIEW 1" src="https://github.com/user-attachments/assets/366bd701-8dd7-4ebb-aec3-0b407274dd4d" />


<img width="1295" height="507" alt="COMPLAINTS VIEW 2" src="https://github.com/user-attachments/assets/3981283b-f9bf-400b-9a8e-1a993fd76b9b" />


## Data Cleaning Process
The following steps were performed using Power Query:

1. Converted the Date_Recieved and Date_Sent column to proper date format
2. Created a Year column for filtering and KPI comparison
3. Created Month and Month Name columns for trend analysis
4. Ensured correct data types for text and numeric fields
5. Checked for and removed duplicate records
6. Identified and handled missing or null values
7. Standardized text fields to ensure consistency
8. Loaded the cleaned dataset into Excel for analysis
9. Renamed some columns to improve clarity and consistency

The following columns were renamed for consistency

| Old Name    | New Name   |
|----------|----------|      

This cleaning process ensures accurate reporting and allows automatic updates when new data is added.



#### View of the dataset after the data cleaning process
<img width="1319" height="477" alt="CLEAN COMPLAINTS VIEW" src="https://github.com/user-attachments/assets/a1f224ab-037a-4f10-867c-ee336e4ee708" />

<img width="1324" height="490" alt="CLEAN COMPLAINTS VIEW 2" src="https://github.com/user-attachments/assets/89579503-3682-4551-8740-86a002f61075" />

## Dashboard Features
The dashboard includes:

- Interactive Year slicer
- Company slicer
- Complaint Issue slicer
- Dynamic KPI cards with logical function
- Line chart for complaint trend analysis
- Bar chart for top complaint issues
- Donut chart for complaint status distribution
- Company performance comparison table

## Key Insights ( 2023–2025 )
1. Complaint Volume Trend

A total of 19,417 complaints were recorded across the three-year period. Complaint levels fluctuate over time, indicating variations in customer experience and service demand.

2. Strong Response Performance

The timely response rate remains consistently high at approximately 99.8%, demonstrating strong compliance and responsiveness from companies in addressing customer complaints.

3. Limited Monetary Relief

Only 12.8% of complaints resulted in monetary relief. This suggests that most complaints were resolved through explanations or non-financial resolutions rather than compensation.

4. Most Frequent Complaint

The most frequent complaint category is "Problem with a purchase shown on your statement",accounting for 4,146 complaints

5. Complaint Trend

Complaint trends fluctuate monthly, showing periods of increased customer dissatifaction

## Business Recommendations

### 1. Review Recurring Complaint Categories

Since certain complaint issues consistently appear among the Top 10, the company should review these categories to identify process gaps or recurring service challenges.

why?

Repeated complaints often indicate underlying operational inefficiencies. Addressing these areas can reduce complaint volume and improve overall customer experience.

### 2. Maintain Strong Response Performance While Improving Resolution Quality

Although the timely response rate is consistently high, the company should continue monitoring resolution effectiveness to ensure complaints are not only answered quickly but resolved properly.

Why?

Fast responses build compliance and trust, but effective resolutions reduce repeat complaints and long-term dissatisfaction.

### 3. Monitor Year-Over-Year Trends Proactively
Since complaint volumes fluctuate across years, management should track performance trends regularly to detect early warning signs of increasing complaints.

Why?

Early monitoring allows the organization to act before issues escalate, improving operational stability and customer satisfaction.

### 4. Enhance Transparency in Complaint Investigations
If many cases are closed with “no error found,” the company should ensure clear communication is provided to customers explaining investigation outcomes.

Why?

Clear explanations improve customer trust, even when the company is not at fault.

### 5. The issue “Problem with a purchase shown on your statement” consistently ranks as the highest complaint category from 2023–2025.
This suggests customers frequently dispute or question charges appearing on their credit card statements.
This may be due to:
- Unrecognized merchant names
- Duplicate charges
- Unexpected subscription renewals
- Delayed transaction postings
- Billing misunderstandings
 
### Recommendation 1: Improve Transaction Transparency

The company should review how purchase transactions are displayed on customer statements to ensure merchant names and transaction details are clear and easily recognizable.
Why?

Unclear or coded merchant descriptions often lead customers to believe a charge is incorrect, even when it is valid. Improving clarity can reduce confusion-based complaints.

### Recommendation 2: Strengthen Customer Education on Billing
The company may consider providing clearer explanations about how transactions post (e.g., pending charges, merchant processing delays, subscription renewals).
Why?

Many disputes arise from misunderstanding rather than actual errors. Better customer awareness can reduce unnecessary complaints.

### Recommendation 3: Analyze Patterns in Disputed Transactions
Management should analyze recurring patterns within this complaint category to determine whether specific merchants, transaction types, or billing processes are driving the issue.
Why?

If certain merchants or transaction types generate repeated disputes, targeted process improvements can significantly reduce complaint volume.

## Business Value
This dashboard provides value by:

- Supporting data-driven decision-making
- Identifying high-risk complaint categories
- Monitoring operational performance
- Improving customer service strategy
## Dataset
### Source : Customer Financial Protection Bureau (CFPB) Complaint Dataset
Filtered from the CFPB complaint database,this dataset contains credit card related to customer complaint records from 2023 to 2025, 

including:
- Complaint date
- Company name
- Complaint issue
- Complaint status
- Timely response indicator
- Monetary relief indicator
## Project Structure
 Files included in this repository:
- Credit Card Complaint Project Data
- Credit Card Complaint Dashboard.xlsx
- Dashboard Screenshot.png
- README.md
## Author
### Sherifat Ahmed

### Aspiring Data Analyst

Skills Demonstrated:

Excel, Power Query, Data Cleaning, Data Analysis, KPI Development, Dashboard Design.
 

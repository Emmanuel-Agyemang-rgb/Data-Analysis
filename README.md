# Customer Retention Analysis — SQL and Power BI

Reducing bank customer churn by turning two messy spreadsheet exports into a clean data model and two focused Power BI dashboards.

## The Problem

A retail bank was losing roughly 1 in 5 customers a year, and nobody could say exactly why. The raw data lived in two linked spreadsheets full of the usual real-world mess that consists of inconsistent country spellings, currency symbols stored as text, a duplicate record. So, before anyone could ask "why are people leaving," the data had to be trustworthy first. This project cleans that data with SQL, then surfaces the patterns that actually predict churn.

## Dataset

10,000 bank customers with demographics (age, gender, geography), account details (balance, tenure, products held, credit card status) and a churn flag. Sourced from two linked tables:

- Customer_Info — 10,001 rows, mixed geography spellings (France / FRA/ French)
- Account_Info — 10,002 rows, balances stored as text (€159660.8), one duplicate CustomerId

## Tools Used

| Tool | Role |
|---|---|
| **SQL** | Cleaning, standardising, and joining the raw tables into one analysis-ready table |
| **Power BI** | Data modelling, DAX measures, and the two dashboard pages |
| **Excel** | Quick sense-checks on the raw exports before writing the cleaning logic |



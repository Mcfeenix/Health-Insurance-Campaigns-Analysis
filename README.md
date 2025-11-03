# Health Insurance Campaigns Analysis
## Project Overview

Founded in **2016**, *PeopleFirst Health* is a medical insurance company serving more than **16,000 customers** across the United States. The company offers four health plan tiers — **Bronze**, **Silver**, **Gold**, and **Platinum** — each designed to meet different customer needs through varying premiums and claim coverage rates.

In **2019**, PeopleFirst Health launched a new set of **12 marketing campaign categories** focused on key themes such as wellness tips, plan affordability, and preventative care. As the company prepares its marketing budget for the upcoming year, it seeks to better understand how these campaigns have performed and how they have influenced customer signups.

This project — conducted in **Tableau** — aims to surface marketing insights and develop actionable recommendations by analyzing campaign performance from **2019 through 2023**, a period that spans the **COVID-19 era**.  

The overarching goal of the marketing budget is to support two primary objectives:
- **Increase awareness** of PeopleFirst Health’s insurance options  
- **Boost customer signups** across all plan types

## Data Structure
The dataset includes three primary tables capturing campaign, customer, and claims information.

<p align="center">
<img width="500" alt="PeopleFirst_ERD" src="https://github.com/user-attachments/assets/1fbebcbc-437f-4912-b81f-77f013798ba3" />
</p>

## North Star Metrics

These metrics measure both reach and conversion effectiveness and are used to compare campaign performance.

| Objective | Metric | Description | Company Results (2019-2023) |
|------------|---------|--------------|----------------|
| **Increase Awareness** | Impressions | Number of times campaign content was displayed | 9M |
|  | Click-Through Rate (CTR) | % of impressions resulting in clicks | 9.4% |
|  | Cost per Impression (CPI) | Cost per display | $0.0066 |
| **Boost Customer Signups** | Customer Signups | Number of new customers | 16,000 |
|  | Cost per Signup | Cost to acquire one new customer | $3.68 |
|  | Signup Rate | % of clicks that resulted in a signup | 1.92% |

## Overall Trends

Customer signup activity showed a clear pandemic-related pattern. In **March 2020**, the number of customer signups **doubled compared to the previous month**, marking the early impact of the COVID-19 pandemic. The trend reached its **peak in April 2020**, with **653 new customer signups** — the highest monthly total in the dataset.  

Signups remained **elevated throughout the first year of the pandemic**, likely driven by increased interest in health coverage, but the **rate of new signups gradually slowed** in subsequent years as conditions stabilized.

<p align="center">
chart placeholder
</p>

## Notable Insights

- **Family Coverage Plan**  
  This campaign recorded no click-through rate (CTR), indicating a possible delivery or data tracking issue. The lack of engagement resulted in zero customer signups. Further investigation is recommended to confirm whether the campaign was properly deployed or if there were data collection errors.

- **Health for All**  
  This campaign achieved **exceptional performance** despite having the **lowest number of impressions (170K)**. It recorded the **highest CTR (25%)**, generated **3,545 new customers**, maintained a **low cost per signup ($1)**, and achieved the **highest signup rate (8%)** among all campaigns. These results suggest highly effective messaging and targeting.

- **Golden Years Security**  
  This campaign underperformed across all key metrics, with **low impressions**, **low CTR**, **few customer signups**, and the **highest cost per signup**. Further analysis could help determine whether the issue stemmed from poor audience targeting or ineffective content.

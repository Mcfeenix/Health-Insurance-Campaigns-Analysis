# Health Insurance Campaigns Analysis

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Data Structure](#data-structure)  
3. [North Star Metrics](#north-star-metrics)  
4. [Overall Trends](#overall-trends)  
5. [Deep Dive](#deep-dive)  
    - [Campaign Performance by Impressions](#campaign-performance-by-impressions)  
    - [Campaign Performance by Customer Signups](#campaign-performance-by-customer-signups)  
6. [Notable Insights](#notable-insights)  
7. [Recommendations and Next Steps](#recommendations-and-next-steps)
8. [Tableau Dashboard Preview](#tableau-dashboard-preview)

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
| **Boost Customer Signups** | Customer Signups | Number of new customers | 16,338 |
|  | Signup Rate | % of clicks that resulted in a signup | 1.92% |
|  | Cost per Signup | Cost to acquire one new customer | $3.68 |

## Overall Trends

Customer signup activity showed a clear pandemic-related pattern. In **March 2020**, the number of customer signups **doubled compared to the previous month**, marking the early impact of the COVID-19 pandemic. The trend reached its **peak in April 2020**, with **653 new customer signups** — the highest monthly total in the dataset.  

Signups remained **elevated throughout the first year of the pandemic**, likely driven by increased interest in health coverage, but the **rate of new signups gradually slowed** in subsequent years as conditions stabilized.

<p align="center">
<img width="700" alt="signup_trends (2)" src="https://github.com/user-attachments/assets/b3a61917-e02e-48ff-bcad-dcb34bdb7cb3" />
</p>

## Deep Dive
The following section breaks down the analysis by individual campaign.

<p align="center">
<img width="700" alt="campaign_spend (2)" src="https://github.com/user-attachments/assets/58d09878-032b-4adf-85f1-9cc4a6930391" />
</p>

### Campaign Performance by Impressions

<div align="center">
  
| Campaign Category | Key Insights |
|------------------|--------------|
| **Top Campaigns (by Impressions)** | • Low Cost per Impression (CPI)<br>• Wide range of Click-through rates (CTR) |
| **Lowest Campaigns (by Impressions)** | • Wide range of Costs per Impression<br>• Notably, **Health for All** campaign had the **highest CTR (25%)** despite **low impressions (171k)** |

</div>

<p align="center">
<img width="700" alt="Impressions" src="https://github.com/user-attachments/assets/5d70fd1a-a909-4d91-b44f-88d02662dbd7" />
</p>

### Campaign Performance by Customer Signups

<div align="center">
  
| Campaign Category | Key Insights |
|------------------|--------------|
| **Top Campaigns (by Signups)** | • High signup rates<br>• Low cost per signup |
| **Lowest Campaigns (by Signups)** | • Low signup rates<br>• High cost per signup<br>• **Golden Years Security** underperformed relative to all other campaigns. |

</div>

<p align="center">
<img width="700" alt="signups (3)" src="https://github.com/user-attachments/assets/94b03e0e-aed4-425b-90e9-2848b8f0dc7f" />
</p>


## Notable Insights

- **#HealthyLiving**  
  This campaign was the only top performer in both impressions and customer signup metrics.

- **Health for All**  
  This campaign achieved **exceptional performance** despite having the **lowest number of impressions (170K)**. It recorded the **highest CTR (25%)**, generated **3,545 new customers**, maintained a **low cost per signup ($1)**, and achieved the **highest signup rate (8%)** among all campaigns. These results suggest highly effective messaging and targeting.
  
- **Family Coverage Plan**  
  This campaign recorded no clicks, resulting in no measurable click-through rate (CTR) or signup rate. Further investigation is recommended to confirm whether the campaign was properly deployed or if there were data collection errors.

- **Golden Years Security**  
  This campaign underperformed across all key metrics, with **low impressions**, **low CTR**, **few customer signups**, and the **highest cost per signup**. Further analysis could help determine whether the issue stemmed from poor audience targeting or ineffective content.

## Recommendations and Next Steps

Based on the campaign analysis from 2019–2023, the following recommendations are suggested to optimize marketing effectiveness and drive both awareness and customer signups:

### 1. Analyze and invest in the #HealthyLiving Campaign
- As a top performer in both impressions and customer signups, this campaign should be studied to identify the key factors behind its success, so that its strategies can be applied to future campaigns.
- Consider allocating a larger portion of the marketing budget to this campaign to maximize ROI.

### 2. Investigate Underperforming Campaigns
- Campaigns like **Golden Years Security** and **Family Coverage Plan** underperformed, either due to low engagement or possible delivery/data issues.
- Conduct a detailed review of campaign content, targeting, and delivery mechanisms to determine causes and opportunities for improvement.

### 3. Explore Opportunities for New Campaigns
- Test new campaign categories or variations that build on the themes of successful campaigns.

### 4. Monitor and Adjust in Real-Time
- Implement ongoing tracking of CTR, impressions, cost per impression, and signup rates.
- Use dynamic dashboards (e.g., Tableau) to quickly identify trends and adjust campaigns as needed for optimal results.
- This screenshot shows the interactive dashboard developed for this project. To explore the live dashboard, [click here](LINK PLACEHOLDER).

<h4 align="center">
Tableau Dashboard Preview
</h4>

<p align="center">
<img width="700" alt="tableau_dashboard" src="https://github.com/user-attachments/assets/12b8f891-8c8e-4ba0-9a11-a4fef2c059d9" />
</p>

![Maven Café Homepage](https://github.com/IkhlasAhmad1998/Power-Bi-Projects/blob/c8a37249e720d9dd729a8949be988c9271b37e38/Maven%20Cafe%20Challenge/images/hompage-with-details.jpg)

# Maven Rewards Challenge - Customer Behavior & Offer Analysis

This repository contains the full analysis and insights derived from the Maven Rewards Challenge, where the goal was to analyze customer behavior and offer effectiveness for [Maven Café](https://mavenanalytics.io/challenges/maven-rewards-challenge/404c6060-60eb-400f-9bce-c3b9f97e9d5a). The project was completed using **Power BI**.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Data Transformation](#data-transformation)
- [Data Modeling](#data-modeling)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Technologies Used](#technologies-used)
- [How to View the Report](#how-to-view-the-report)
- [License](#license)

## Project Overview
The purpose of this project was to:
- Understand customer behavior in response to different promotional offers.
- Identify key customer segments.
- Develop a data-driven strategy for future promotional messaging and targeting.

The analysis focuses on customer demographics, spending habits, and offer performance across different channels.

## Data Source
The dataset consists of:
1. **Customer Data**: Demographic information (age, income, gender).
2. **Offer Data**: Types of offers, channels used, and reward information.
3. **Events Data**: Events information.

## Data Transformation
Data transformation was conducted using **Power BI**:
- Loaded CSV files for customers, offers, and transactions.
- Cleaned and standardized data for analysis, transforming time variables (offers in days, events in hours).
- Split the `events` table to separate transactions from offer-related events for clearer analysis.

## Data Modeling
Data modeling involved linking the tables based on unique identifiers:
- **Customers** linked with **Transactions** and **Offers** via `customer_id` and `offer_id`.
- Created a bridge table between offers and channels to maintain offer integrity.

## Insights
Key findings from the analysis include:
- The largest customer group is aged 45-64, followed by 65+.
- Most customers earn between $0-60k, with moderate spenders (70$-250$) generating the highest revenue.
- 2017 had the most new members and transactions, but 2018 saw a sharp decline in transaction volume.
- The offer completion rate is low (24.17%), with discount offers generating the most revenue.

## Recommendations
Based on the insights, the following strategies are recommended:
1. **Target Age 45-64**: Focus on personalized offers to this segment, who generate the most transactions and completed offers.
2. **Engage Moderate and Low Spenders**: Increase basket size through discounts and loyalty programs.
3. **Improve Offer Completion Rates**: Use multi-channel promotions (web, email, mobile, social) to boost engagement.
4. **Attract Younger Audiences**: Develop mobile-first campaigns to engage customers under 45.
5. **Tailor Offers for High Spenders**: Create exclusive offers and loyalty programs for high-value customers.

## Technologies Used
- **Power BI**: Used for data transformation, modeling, and creating dashboards for visual insights.
- **DAX**: Applied to perform advanced calculations and metrics.

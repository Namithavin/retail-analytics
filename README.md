# UAE E-Commerce Analytics: Product Performance, Seasonality & Sentiment Analysis

[![Tableau Public](https://img.shields.io/badge/Tableau_Public-Interactive_Dashboard-orange?logo=tableau)](https://public.tableau.com/views/UAEE-CommerceDataAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
[![BigQuery](https://img.shields.io/badge/Google_Cloud-BigQuery_SQL-blue?logo=googlecloud)](https://cloud.google.com/bigquery)
[![SQL](https://img.shields.io/badge/Dialect-Standard_SQL-4479A1?logo=postgresql)](https://cloud.google.com/bigquery/docs/reference/standard-sql/query-syntax)

## Project Overview
This project delivers an end-to-end retail business intelligence solution analyzing product performance, price elasticity, payment gateway distributions, and seasonal surges across the seven United Arab Emirates. 

Using raw e-commerce transaction data, data modeling was executed in **Google Cloud BigQuery** (ETL, schema normalization, deduplication, unpivoting) and visualized via a multi-layered, interactive 2×2 dashboard in **Tableau Public**.

---

## Executive Dashboard Architecture
An interactive 4-sheet operational dashboard structured for regional category leads and supply chain planners:

| View | Metric Tracked | Business Impact |
| :--- | :--- | :--- |
| **Emirate Sales Map** | Regional Revenue (AED) & Unit Velocity | Highlights geographic demand clusters (Dubai & Abu Dhabi lead with 70%+ volume). |
| **Sentiment vs. Revenue** | Review Score (1.0–5.0) vs. Product Revenue | Pinpoints high-volume, low-rating products posing critical customer churn and return risks. |
| **12-Month Demand Run-Rate** | Monthly Sales Run-Rates with Peak Reference Bands | Captures demand surges around Ramadan/Eid (Months 3–4) and White Friday (Month 11). |
| **Payment Gateway Share** | COD vs. Digital (Card, Apple Pay) vs. BNPL (Tabby, Tamara) | Quantifies checkout friction and Return-to-Origin (RTO) risk across regional markets. |

---

## Technical Data Pipeline

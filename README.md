# rana_analytics_sql
SQL analysis of hospital management data

# Hospital SQL Analytics Project

## Overview
This project analyzes a synthetic hospital management dataset using SQL to explore patient utilization, doctor workload, treatment costs, billing behavior, and insurance performance.

## Objectives
- Analyze patient visit patterns and appointment outcomes
- Evaluate doctor workload and specialization demand
- Identify high-cost treatments and cost trends
- Examine billing status and payment behavior
- Assess insurance usage and pending payment risk

## Tools
- PostgreSQL (w/ DBeaver)
- SQL (Joins, Aggregations, Window Functions)
- Tableau (for visualization)

## Dataset
The dataset consists of multiple tables simulating a hospital management system from Kaggle.com:
- patients
- doctors
- appointments
- treatments
- billing

All data is synthetically generated for educational/demo/practice purposes.

## Key Insights
- Patient visits fluctuate monthly with a notable proportion of non-completed appointments.
- Doctor workload varies significantly across specializations.
- A small number of treatment types contribute disproportionately to total treatment costs.
- Insurance payments exhibit higher pending rates compared to direct payment methods.

## Next Steps
- Build interactive dashboards using Tableau

## SQL Analysis Structure

The analysis is organized into the following SQL files:

- `patient_utilization.sql`  
  Analysis of active patients, appointment trends, and visit outcomes.

- `doctor_workload.sql`  
  Evaluation of doctor workload, appointment volume, and specialization demand.

- `treatment_cost_analysis.sql`  
  Analysis of treatment costs, cost drivers, and temporal cost trends.

- `billing_payment_analysis.sql`  
  Examination of billing status, payment methods, and payment success rates.

- `insurance_insight.sql`  
  Analysis of insurance usage patterns and pending payment risks.


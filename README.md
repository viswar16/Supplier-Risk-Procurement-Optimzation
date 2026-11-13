# Supplier Risk & Procurement Cost Optimization

### Python | Pandas | NumPy | Power BI | DAX | Supply Chain Analytics

An end-to-end procurement analytics project focused on evaluating supplier delivery performance, identifying operational risks, prioritizing supplier reviews, and modeling potential procurement cost savings.

## 1. Project Overview

Supplier performance directly influences procurement costs, delivery reliability, and supply chain resilience.

This project analyzes 1,000 procurement orders across 30 suppliers to identify delivery delays, evaluate supplier risk, and recommend data-driven procurement actions.

The analysis combines Python-based data processing, supplier scorecards, risk prioritization, financial scenario modeling, and interactive Power BI dashboards.

## 2. Business Objectives

- Evaluate supplier delivery performance and reliability.
- Identify suppliers requiring prioritized procurement reviews.
- Analyze procurement spending and supplier concentration.
- Develop supplier performance scorecards.
- Evaluate the sensitivity of supplier risk rankings.
- Estimate potential savings under hypothetical cost-reduction scenarios.
- Communicate findings through interactive Power BI dashboards.

## 3. Dataset Overview

| Metric | Value |
|---|---:|
| Total Procurement Orders | 1,000 |
| Total Suppliers | 30 |
| Total Procurement Spend | $25,290,073.67 |
| Delayed Orders | 514 |
| Overall Delay Rate | 51.4% |
| Severe Delays (6+ Days) | 107 |
| Severe Delay Rate | 10.7% |

**Data source:** [Public supply chain dataset repository](https://github.com/AnkitBijalwan33/supply-chain-risk-dashboard)

The source dataset represents a general supply chain procurement scenario and is not specific to automotive manufacturing.

## 4. Tools & Technologies

| Technology | Application |
|---|---|
| Python | Data analysis and processing |
| Pandas & NumPy | Data cleaning, transformation, and calculations |
| Jupyter Notebook | Reproducible analytical workflow |
| Power BI | Interactive procurement dashboards |
| DAX | KPI measures and financial calculations |
| CSV | Processed analytical datasets |

## 5. Analytical Methodology

### Data Preparation

Validated procurement records, reviewed missing values and duplicates, checked numerical and date fields, and prepared analytical datasets.

### Supplier Performance Analysis

Developed supplier-level scorecards incorporating procurement spend, order volumes, delivery delay rates, and severe delay rates.

### Supplier Risk Prioritization

Calculated a weighted, normalized risk priority score to support supplier review decisions.

Evaluated supplier rankings under three weighting scenarios to assess ranking stability.

The priority score is a decision-support ranking metric, not a calibrated probability of supplier failure.

### Procurement Cost Optimization

Modeled hypothetical procurement cost reductions of 2%, 3%, and 5% across selected priority suppliers.

Calculated the corresponding potential savings and their impact on total procurement spend.

## 6. Key Findings

Four suppliers — **S4, S24, S21, and S23** — consistently emerged as high
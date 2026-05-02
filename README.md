# CareEscapes AI — Medical Tourism Analytics

> **Course:** ALY 6080 Integrated Experiential Learning · Northeastern University · Winter 2026
> **Role:** Graduate Data Analyst (Sponsor Project)
> **Sponsor:** CareEscapes AI — AI-powered medical tourism platform

**[View Portfolio Case Study](https://ankita-pichuka.netlify.app/careescapes-ai-portfolio-final)** &nbsp;·&nbsp; **[LinkedIn](https://linkedin.com/in/ankita-pichuka)**

---

## Overview

CareEscapes AI is building a platform that helps patients find affordable global healthcare, reduce wait times, and make transparent, data-backed treatment decisions. I joined as a graduate analyst to provide the data foundation for their AI recommendation engine.

This repository contains the full exploratory data analysis, Power BI dashboard work, and strategic recommendations delivered to the founding team.

---

## The Problem

Patients exploring medical tourism face three core barriers:

- **Fragmented pricing** — no single place to compare total cost (treatment + travel + accommodation) across countries
- **Hidden cost structure** — most platforms show treatment price only, ignoring the dominant cost driver
- **Wait-time opacity** — domestic wait times of 6–12 months vs. 5 days abroad, but no tool surfaces this tradeoff

---

## Key Findings

| Finding | Detail |
|---|---|
| **Airfare dominates patient cost** | ~58% of total spend, stable across all years and volume scenarios |
| **60–75% treatment savings abroad** | Full Arch Restoration: $32,500 in the US vs. $10,750 in Mexico |
| **270 days vs. 5 days** | Full Mouth Restoration wait time: domestic vs. abroad |
| **45:1 LTV-to-CAC ratio** | $21K–$36K LTV against $460 CAC validates aggressive acquisition |
| **Cost structure never changes** | 58.14% airfare / 23.26% treatment / 18.60% hotel — constant across Year 1 to Year 5 |

---

## Methodology

### 1. Exploratory Data Analysis
Started by profiling the multi-tab financial plan — treatment costs across 4 countries, travel expenses, 5-year operational projections, and per-patient cost breakdowns. Goal was to understand the shape of the data before drawing any conclusions.

### 2. Cost Structure Decomposition
Built a per-patient cost model to break total spend into components. The airfare finding (58% of cost) was the most actionable insight — it redirected partnership strategy from clinic-only to travel-integrated.

### 3. Global Destination Benchmarking
Compared full cost of care (treatment + flight + hotel) across USA, Canada, Mexico, and Costa Rica. Complex procedures showed the strongest case for medical tourism, even after accounting for all travel costs.

### 4. Wait-Time Analysis
Mapped domestic vs. international wait times across all four procedures. Identified wait-time reduction as a separate, non-price conversion driver — especially powerful for urgent and complex cases.

### 5. Power BI Dashboard Development
Built an 11-page interactive dashboard covering:
- Expense distribution treemap
- Patient cost breakdown by year
- Profit range projections (Year 1 to Year 5)
- Cost structure stability analysis (100% stacked)
- Expense category scaling comparison
- Scatter analysis: profit vs. patient volume growth

---

## Recommendations

1. **Airline partnerships** — airfare is 58% of cost; bulk fares or co-branded bundles are the single highest-leverage cost reduction
2. **Bundled pricing model** — combine treatment + flight + hotel into one package to remove decision friction
3. **Transparent total-cost dashboard** — show full cost comparisons, not just treatment price
4. **AI recommendation engine inputs** — budget threshold, urgency tier, and procedure complexity fully stratify the patient decision space

---

## Repository Structure

```
CareEscapes-AI-Analytics/
│
├── data/
│   └── careescapes_financial_plan.xlsx     # Source financial dataset
│
├── dashboard/
│   └── Group_Project_EDA_Subgroup_Analysis.pbix   # Power BI report (11 pages)
│
├── portfolio/
│   └── careescapes-ai-portfolio-final.html  # Interactive portfolio case study
│
└── README.md
```

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data cleaning, cost modeling, financial plan analysis |
| Power BI | 11-page interactive dashboard, DAX measures |
| HTML / CSS / JavaScript | Interactive portfolio case study with Chart.js |
| Chart.js | Recreated all 11 Power BI visuals as interactive web charts |

---

## Skills Demonstrated

`Exploratory Data Analysis` `Cost Modeling` `Business Analytics` `Power BI` `DAX` `Data Storytelling` `Stakeholder Communication` `Competitive Benchmarking` `Financial Plan Analysis` `Strategic Recommendations`

---

## Business Impact

- Validated 45:1 LTV-to-CAC ratio through financial modeling
- Airfare finding redirected partnership strategy toward travel-integrated bundling
- Delivered 11-page Power BI dashboard used by founding team for investor discussions
- Projected Year 5 revenue of $105M–$180M supported by cost analysis

---

## About

**Ankita Pichuka** — M.S. Analytics (Applied Machine Intelligence), Northeastern University (expected May 2027)

Actively seeking Summer/Fall 2026 co-ops in data science, analytics, and machine learning.

[ankita-pichuka.netlify.app](https://ankita-pichuka.netlify.app) &nbsp;·&nbsp; [linkedin.com/in/ankita-pichuka](https://linkedin.com/in/ankita-pichuka) &nbsp;·&nbsp; ankitapichuka@gmail.com

# primary-care-access-failure-index
Measuring healthcare access pressure in Saskatchewan using ED utilization, population, workforce, and community health data

# Primary Care Access Failure Index (PCAFI)

## Overview
The **Primary Care Access Failure Index (PCAFI)** is a composite index designed to quantify pressure on the healthcare system by measuring failures in access to primary care.  
It uses emergency department utilization, population dynamics, workforce availability, and community health indicators to estimate where and when primary care gaps are most acute.

This project focuses on **Saskatchewan**, with methods designed to be extensible to other provinces or regions.

---

## Why This Project Matters
When primary care access fails, patients do not disappear — they show up elsewhere:
- Emergency Departments
- Urgent care centers
- Delayed treatment pathways

This index provides a **data-driven way** to:
- Identify systemic stress points
- Support policy analysis
- Inform workforce planning
- Enable evidence-based health system discussions

In short: *ED overcrowding is a symptom. This index looks for the cause.*

---

## Key Questions This Project Answers
- Where is primary care access breaking down?
- How does ED usage scale relative to population growth?
- Are healthcare resources keeping pace with demand?
- Can multiple indicators be combined into a single, interpretable signal?

---

## Data Sources
All datasets used are **publicly available**.

| Dataset | Source | Description |
|------|------|------|
| Emergency Department Visits | CIHI / Provincial Open Data | Annual ED visit counts |
| Population Estimates | Statistics Canada | Yearly population by region |
| Health Workforce Data | Statistics Canada / CIHI | Physicians, nurses, primary care supply |
| Community Health Indicators | Provincial Open Data | Supplementary system context |

Detailed documentation is available in **`data_sources.md`**.

---


# High Blood Pressure Risk Factors in Bangladesh
## Statistical Analysis of BDHS 2022 Data | IBM SPSS Statistics

**Analyst:** Rokaiya Raisa | BSc Microbiology, BRAC University  
**Tools:** IBM SPSS Statistics  
**Dataset:** Bangladesh Demographic and Health Survey (BDHS) 2022  
**Sample Size:** 10,086 participants across 8 divisions  

---

## Project Overview

This project analyzes the prevalence and associated risk factors 
of high blood pressure (HBP) in Bangladesh using data from the 
nationally representative BDHS 2022 survey.

Both descriptive and inferential statistical techniques were applied:
frequency analysis, Chi-square tests, Pearson correlation, and 
simple linear regression — all conducted in IBM SPSS Statistics.

---

## Key Finding

**17.5% of 10,086 Bangladeshi adults reported clinician-diagnosed 
high blood pressure.** Prevalence varied significantly across 
demographic, socioeconomic, and lifestyle factors.

---

## Variables Analyzed

| Variable | Type |
|----------|------|
| Geographic Division | Categorical |
| Residence Type (Urban/Rural) | Categorical |
| Marital Status | Categorical |
| Diabetes Status | Categorical |
| Education Level | Categorical |
| Wealth Index | Categorical |
| Smoking Status | Categorical |
| Caffeinated Drink Consumption | Categorical |
| Age | Continuous |
| Systolic Blood Pressure | Continuous |
| HBP Status (outcome) | Binary |

---

## Chi-Square Results Summary

| Risk Factor | Chi-Square | p-value | HBP Prevalence |
|-------------|-----------|---------|----------------|
| Marital Status | 313.594 | <0.001 | Widowed: 36.1% |
| Diabetes Status | 94.316 | <0.001 | Diabetics: 44.7% |
| Education Level | 99.393 | <0.001 | No education: 23.5% |
| Wealth Index | 88.983 | <0.001 | Richest: 22.5% |
| Caffeine Use | 38.344 | <0.001 | Consumers: 25.5% |
| Division | 27.133 | <0.001 | Barisal: 21.0% |
| Smoking | 31.446 | <0.001 | Smokers: 22.4% |
| Residence Type | 13.604 | <0.001 | Urban: 19.3% |

All associations statistically significant at p < 0.001.

---

## Correlation & Regression

- **Pearson r = 0.308** — weak-to-moderate positive correlation 
  between age and systolic BP
- **B = 0.582** — for every 1 year increase in age, systolic BP 
  rises by ~0.582 mmHg
- **R² = 0.095** — age explains 9.5% of BP variation
- **Data quality note:** One extreme outlier (996 mmHg) identified 
  as a data entry error — flagged and noted in analysis

---

## Files in This Repository

| File | Description |
|------|-------------|
| `HBP_Risk_Factors_Bangladesh_BDHS2022.pdf` | Portfolio-ready analysis report with charts |
| `BTE317_Full_Statistical_Analysis.pdf` | Full SPSS output and detailed methodology |
| `BDHS2022_cleaned_data.csv` | Cleaned dataset used for analysis |

---

## Skills Demonstrated

`SPSS` `Chi-Square Testing` `Pearson Correlation` `Linear Regression`  
`Descriptive Statistics` `Public Health Data Analysis`  
`Data Quality Assessment` `Scientific Reporting`

---

## Data Source

Bangladesh Demographic and Health Survey (BDHS) 2022  
[https://dhsprogram.com/](https://dhsprogram.com/)

# Screen_Time_Childhood-Obesity_Dietary-Intake_Using-NHANES-2021-2023
Survey-weighted NHANES 2021–2023 analysis examining the association between daily screen time and obesity among U.S. children aged 6–18 years and evaluating the mediating role of dietary intake using descriptive statistics and multivariable logistic regression in SAS.

## Overview
Childhood obesity remains a major public health concern in the United States. This project examines whether higher daily screen time is associated with increased odds of obesity among U.S. children aged 6–18 years using nationally representative NHANES 2021–2023 data. The analysis also explores whether dietary intake (total sugar and fat consumption) may help explain this relationship.

# Purpose
This repository contains an applied epidemiology research project conducted to demonstrate survey-weighted data analysis using NHANES. The goal was to quantify the association between screen time and childhood obesity and assess the potential mediating role of dietary behaviors using reproducible statistical methods.

# Study Design
* Cross-sectional analysis of NHANES 2021–2023
* Population: U.S. children and adolescents aged 6–18 years
* Final analytic sample: 17,197 participants
* Nationally representative estimates using survey weights

# Variables
Exposure
* Daily screen time (self-reported hours/day)
  * Low: <2 hours
  * Moderate: 2–4 hours
  * High: >4 hours

Outcome
* Obesity status (BMI ≥ 30 kg/m²)

Covariates
* Age
* Sex
* Total sugar intake (g/day)
* Total fat intake (g/day)

Survey Design
* Strata, clusters, and examination weights (NHANES complex sampling)

# Methods
* Survey-weighted descriptive statistics
* Chi-square tests and mean comparisons
* Logistic regression (crude and adjusted models)
* Survey-weighted logistic regression (PROC SURVEYLOGISTIC)
* Conducted in SAS 9.4

# Key Findings
* 25.7% of children reported >4 hours/day of screen time
* Obesity prevalence was highest among high screen time users (~19%)
* High screen time was associated with ~2.4× higher odds of obesity after adjustment
* Moderate screen time was not significantly associated with obesity
* Dietary intake did not fully explain the association

# Data
* NHANES public-use datasets are available from the CDC: https://www.cdc.gov/nchs/nhanes/

To reproduce results, download:

Demographics

BMI/Body measures

Physical activity (screen time)

Dietary intake (24-hour recall)


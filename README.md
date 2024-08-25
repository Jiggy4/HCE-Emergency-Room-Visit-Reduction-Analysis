# Project Architecture for Analyzing Emergency Room Visit Reduction and Food Insecurity in New England

## Overview
This project focuses on understanding the relationship between food insecurity and emergency room (ER) utilization across New England counties. The goal is to determine if psychosocial factors, such as food insecurity, drive higher ER use and to develop strategies to address these disparities. The project also aims to recommend interventions to reduce ER visits at Good Health Physicians.

## Data Description
### Dataset 1: ER Visit Reduction at Good Health Physicians
- **Dataset Size:** Details not specified
- **Features:** Variables related to healthcare access and ER utilization
- **Target Variable:** Reduction in ER visits to meet the annual target of 450 visits per 1000 members

### Dataset 2: Food Insecurity and ER Utilization in New England
- **Dataset Size:** County-level data across New England states
- **Features:** `YEAR`, `STATE`, `COUNTY`, `# FFS BENEFICIARIES`, `AVG RISK SCORE`, `ER VISITS PER 1000`, `% FOOD INSECURE`
- **Target Variable:** Correlation between food insecurity and ER utilization and average risk score by county

## Technology Stack
- Data Analysis: Excel
- Exploratory Data Analysis (EDA): Excel for visual insights into the data distribution and relationships.
- **Models and Analysis:**
  - ROI Analysis for ER Visit Reduction Strategies
  - Correlation Analysis between Food Insecurity and ER Utilization/Average Risk Score

## Intervention Options for ER Visit Reduction
**Option 1: Hiring an Additional Practitioner**
- **Impact:** Reduces ER visits per 1000 to 472.5 in the first year, 448.9 in the second and third years.
- **ROI:** 315.49% in the first year, 463.493% in the second year, 486.73% in the third year.

**Option 2: Building an Additional Urgent Care Center**
- **Impact:** Reduces ER visits to approximately 446 visits per 1000 each year, maintaining this reduction over three years.
- **ROI:** 136.34% in the first year, 141.68% in the second year, 146.19% in the third year.

**Option 3: Adding a New Phone Line Staffed by Triage Nurses**
- **Impact:** Reduces ER visits per 1000 to 472.5 in the first year, 448.9 in the second and third years.
- **ROI:** 576% in the first year, 890.8% in the second year, 924.97% in the third year.

## Analysis of Food Insecurity and ER Utilization
- **Component A:** Developed a dataset showing average risk score and ER visits per 1000 for each county in New England in 2021, along with the 2021 “% food insecure” from the County Health Rankings dataset.
- **Component B:** Conducted a visual analysis showing the correlation between food insecurity and:
  - ER utilization
  - Average risk score by county

## Practical Applications
- **Targeted Interventions:** Selecting the optimal intervention to reduce ER visits while maximizing return on investment.
- **Policy Development:** Informing decisions regarding healthcare resource allocation, especially in areas with high food insecurity.

## Recommendations
- **Preferred Solution for ER Reduction:** Adding a new phone line staffed by triage nurses is recommended for substantial ROI and achieving the ER visit reduction target.
- **Outcome:** Enhances patient satisfaction by ensuring timely and appropriate care guidance, aligns with Good Health's mission, and addresses healthcare disparities influenced by food insecurity.

## Limitations
- The data set and scope are limited to the current service area and may not capture broader healthcare trends.
- Selection bias and the exclusion of counties with fewer than 10,000 CMS beneficiaries could impact the generalizability of the results.

## Future Work
- Extend the study to include more comprehensive and diverse datasets.
- Update the analysis to capture current trends and emerging factors affecting ER utilization and food insecurity in the healthcare industry.

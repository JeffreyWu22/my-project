# Global Healthcare OOP Costs Exploration

## Overview

This project analyzes data from the Global Health Expenditure Database (GHED), a dataset curated by the World Health Organization. The dataset includes time series data from 2000 to 2022, detailing country-level health expenditure metrics across various regions and income levels. The primary objective is to explore trends and relationships in healthcare financing, government intervention, and disease-specific spending to uncover actionable insights for policymakers and stakeholders. Our analysis primarily focuses upon out-of-pocket (OOP) costs.

---

## Objectives

1. Examine disease specific spending rates by region

2. Identify how OOP costs influence healthcare outcomes

3. Quantify expenditure allocation and its impact on OOP costs

4. Test how government spending impacts OOP spending

---

## Conclusions

- Data Challenges:
  - Vaccine and specific healthcare spending data have many missing values, limiting meaningful comparisons.
  - Regional variations in predominant diseases are observable despite data gaps.

- Healthcare Funding by Region and Income:
  - Stark differences exist in healthcare spending allocation based on region and income level.
  - Presence of outliers suggests other factors influencing healthcare funding decisions.

- Insurance and Out-of-Pocket Costs:
  - Low-income countries with minimal government healthcare spending show varying reliance on private insurance to offset costs.
  - Some countries successfully utilize private insurance, while others struggle—highlighting a need for further investigation.

- Key Questions for Future Exploration:
  - Why do some low-income countries have lower out-of-pocket costs despite limited government spending?
  - Investigate roles of external funding, voluntary contributions, and cultural or policy factors in reducing financial burdens.
  - Examine and categorize policy changes to identify effective strategies for aid delivery and resource optimization.

--- 

## Interaction with Repository

Please visit [the posit website](https://posit.co/download/rstudio-desktop/) for instructions on how to download R and Studio to run this repository. 

We utilize the renv package for package management. Please see [this link](https://rstudio.github.io/renv/articles/renv.html) for information on how you can set up the required environment to re-run our code. 

Finally, the most effective way to interact with our code is to first examine the excel file included in this repository. It contains a code book which will allow you to understand what variables are available. Changing some variable names may allow you to obtain similar insights, albeit about different variables, with our template. 
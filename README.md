# LMPD Traffic Stop Analysis
Data analysis project exploring how racial dynamics between drivers and officers influence search likelihood during traffic stops in Louisville’s wealthiest and poorest divisions.
This project investigates how racial dynamics between drivers and officers affect the likelihood of a search during traffic stops in two contrasting divisions of Louisville, Kentucky—Division 2 (least affluent) and Division 8 (most affluent).

## 🔍 Research Question

How do racial dynamics between drivers and officers affect the likelihood of a search during traffic stops in Louisville's richest and poorest divisions, and how do these effects vary by time of day?

## 📊 Dataset

- Citations and searches from 2019 to 2022 for Black and White drivers and officers.
- Covers two zip codes:
  - **Division 2 (40202)**: Median income ~$5,856, 86.4% Black
  - **Division 8 (40206)**: Median income ~$175,156, 94.9% White
- Time categorized as:
  - **Daytime**: 6 AM – 6 PM
  - **Nighttime**: 6 PM – 6 AM

## 🧠 Methods

- Conducted Exploratory Data Analysis (EDA) to understand search rates across divisions, times, and racial dynamics.
- Fitted four logistic regression models (day/night x Division 2/8) to estimate the likelihood of a search given officer and driver race.
- Used predicted probabilities and odds ratios to compare search likelihoods.

## 📌 Key Findings

- Drivers are more likely to be searched at night than during the day.
- Officers tend to search drivers of their own race more often—especially at night.
- In Division 8, a White officer is significantly more likely to conduct a search, regardless of the driver's race.
- In Division 2, Black officers are more likely to search Black drivers than White officers are.

## ⚠️ Limitations

- Independence assumption in logistic regression may be violated.
- Socioeconomic status was simplified using only median income.
- Only includes Black and White racial dynamics.
- Potential underlying biases in data collection and recording.

## 👥 Team

- Michael Okanta
- Thao Nguyen

## 📁 Files Included

- Data and cleaned datasets from 2019 to 2022
- R scripts for analysis
- Powerpoint presentation upon analysis 
- PDF of DOJ Investigation of LMPD
- LMPD divisions map


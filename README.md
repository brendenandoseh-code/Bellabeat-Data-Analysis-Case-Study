# Bellabeat-Data-Analysis-Case-Study
This project was completed as part of the Google Data Analytics Professional Certificate capstone, extended with a second dataset and cross-dataset validation methodology to strengthen the analytical foundation.

## Overview

Bellabeat is a high-tech wellness company that designs health-focused smart products for women. This analysis examines consumer behavior data from non-Bellabeat smart devices to identify usage trends that could inform Bellabeat's marketing strategy. Two independent datasets were analyzed to strengthen the reliability of findings and address the limitations inherent in any single data source.

## Datasets

| | FitBit Fitness Tracker | LifeSnaps |
|---|---|---|
| **Users** | 33 | 71 |
| **Duration** | 31 days | 4 months |
| **Year** | 2016 | 2021–2022 |
| **Location** | US | Europe (Greece, Cyprus, Italy, Sweden) |
| **Demographics** | None | Age, gender, BMI |
| **Source** | Kaggle (CC0) | Kaggle / Zenodo (Nature Scientific Data) |

## Key Findings

- **Sedentary behavior dominates:** 100% of FitBit users and 97% of LifeSnaps users averaged over 10 sedentary hours per day — even those classified as Active
- **Sedentary time is linked to shorter sleep:** Both datasets showed a moderate-to-strong negative correlation (r = -0.601 and r = -0.583) between sedentary minutes and sleep duration
- **Activity levels are consistent across populations:** Average daily steps were remarkably similar across both datasets (8,319 vs 8,413) despite being collected five years apart on different continents
- **Female users are more active:** Women logged more steps, more active minutes, and more sleep than men in the LifeSnaps data — relevant to Bellabeat's female-focused audience
- **Users engage passively, not actively:** Participation dropped sharply for features requiring manual input (weight logging, mood tracking) compared to passive tracking (steps, heart rate)

## Recommendations

1. Make inactivity alerts and movement reminders a core product feature
2. Market sleep and activity tracking as an integrated wellness story
3. Use personalized, progressive goals rather than fixed benchmarks
4. Target low-activity days with timed notifications and campaigns
5. Prioritize passive tracking features over manual logging
6. Position Bellabeat for women who are already health-engaged and seeking deeper insight

## Tools & Skills

- **Python** (pandas, matplotlib)
- **Jupyter Notebook**
- Data cleaning and validation
- Exploratory data analysis
- Cross-dataset comparison
- Stakeholder-facing narrative and recommendations

## File Structure

# Netflix Content Recommendation Analysis (Excel)

## Project Overview
This project demonstrates how user viewing behaviour can be analysed using Excel to build a correlation-based Netflix recommendation model that identifies shows commonly watched together.

The aim of the project is to show how simple statistical techniques, when applied correctly, can support real-world business decisions such as content recommendation.

---

## Business Problem
Streaming platforms like Netflix rely on personalised recommendations to increase user engagement and retention.
This project explores how viewing patterns can be used to recommend relevant shows based on similarity in user behaviour rather than assumptions.

---

## Dataset Description
The dataset represents viewing behaviour of approximately 2,000 subscribers across multiple Netflix shows and includes:
- Subscriber ID
- Show Name
- Episodes Watched
- Average Episode Duration (minutes)

---

## Methodology
1. Created a new engagement metric (**Total Minutes Watched**) to standardise viewing behaviour across shows.
2. Transformed raw transactional data using Pivot Tables to make it suitable for analysis.
3. Applied correlation analysis to measure relationships between shows.
4. Used conditional formatting and scatter plots to validate and visualise correlations.
5. Interpreted results to justify show recommendations based on viewing similarity.

---

## Key Insights
- Shows with strong positive correlation are suitable recommendation candidates.
- *Dahmer* shows a strong correlation with *You* (0.95) and *Dexter* (0.82), indicating shared viewing behaviour.
- Weak or near-zero correlation indicates little to no relationship between shows.
- Simple correlation-based models can effectively demonstrate recommendation logic.

---

## Tools & Skills Used
- Microsoft Excel  
- Data Wrangling  
- Feature Engineering  
- Pivot Tables  
- Correlation Analysis  
- Descriptive Analytics  
- Data Visualisation  
- Business Insight Generation  

---

## Files in This Repository
- Excel file containing the full analysis
- Screenshots demonstrating correlation matrix and scatter plots

---

## Notes
This project focuses on analytical thinking and business insight rather than advanced machine learning, making it suitable for entry-level and junior data analyst roles.

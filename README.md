# A Data-Driven Analysis of Factors Influencing the Severity and Societal Impact of Mass Shooting Incidents

This project explores the complex dynamics behind mass shootings in the United States, aiming to identify the factors that influence their frequency, severity, and societal impact. It incorporates data-driven methods and advanced statistical models to generate insights for policymakers, researchers, and law enforcement agencies.

## Supervisor
Dr. Rong Pan

---

## Project Objectives

1. **Community Analysis**:
   - Investigate how community characteristics (e.g., socioeconomic factors, mental health resources, and gun store density) correlate with mass shooting frequency.

2. **Firearm Characteristics**:
   - Analyze the role of firearm modifications (e.g., extended magazines and caliber) in casualties and years of life lost.

3. **Temporal Trends**:
   - Examine trends in mass shootings over time and forecast future incidents using time-series models.

4. **Victim Demographics**:
   - Assess the relationship between victim demographics (age, gender, race) and societal costs like life expectancy loss.

5. **Clustering Insights**:
   - Apply clustering methods to identify patterns and groupings within mass shooting data.

---

## Data Sources

The analysis is based on four major datasets:
- **Firearms Data**: Characteristics and acquisition methods of firearms used.
- **Victim Data**: Demographics and relationships to perpetrators.
- **Community Data**: Socioeconomic factors and mental health resources.
- **Trend Data**: Historical mass shooting trends (1966–2021).

---

## Methodologies

- **Exploratory Data Analysis (EDA)**:
  - Visualization tools: heatmaps, scatter plots, pie charts.
  - Outlier detection and missing value handling.
  
- **Inferential Statistics**:
  - Correlation analysis, ANOVA, regression models.

- **Machine Learning Models**:
  - Logistic Regression, Decision Trees, Random Forest, Gradient Boosting Machines (GBM).
  - Time-series forecasting using ARIMA and Holt-Winters smoothing.

- **Clustering Techniques**:
  - K-Means, Deep Embedded Clustering (DEC).

---

## Results and Insights

1. **Community Factors**:
   - Higher gun store density correlates moderately with legal purchases.
   - Socioeconomic challenges like high rental unit percentages associate with more shootings.

2. **Firearm Characteristics**:
   - Modifications like extended magazines have a modest effect on casualties but are overshadowed by contextual factors.

3. **Temporal Trends**:
   - Mass shootings are increasing over time, with peaks in incidents around 2015.
   - Forecasts suggest this trend will persist.

4. **Victim Demographics**:
   - Younger individuals are increasingly falling victim to gun violence.

5. **Clustering**:
   - Identified high-impact years and recurring patterns using DEC.

---

## Challenges

- Missing data and outliers affected initial analyses.
- Imbalanced datasets required oversampling methods like SMOTE.
- Computational complexities addressed through parallel processing.

---

## Tools and Technologies

- Python (pandas, scikit-learn, statsmodels, matplotlib, seaborn)
- Jupyter Notebook
- ARIMA and clustering libraries

---

## Future Work

- Integrate mental health indicators for more comprehensive insights.
- Address racial and demographic disparities in future models.
- Explore policy implications for reducing mass shooting frequency and impact.

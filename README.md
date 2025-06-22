# Coffee Quality Analysis

This project explores a global coffee quality dataset using Python. The goal is to identify key factors that affect cup scores such as species, country of origin, processing method, defects, and sensory attributes like aroma and flavor.

---

## Project Overview

- **Dataset**: Coffee quality evaluation data from professional graders
- **Rows**: 13,340 coffee samples
- **Columns**: 44 features including farm details, processing methods, quality scores, defects, altitude, and certifications
- **Tools**: Python, Pandas, Seaborn, Matplotlib, Scipy

---

## Objectives

- Understand what factors influence coffee quality
- Identify top-performing species, countries, and farms
- Compare cup scores based on processing methods and sensory attributes
- Validate insights using hypothesis testing

---

## Techniques Used

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Grouping, Aggregation, and Filtering
- Correlation Analysis
- Data Visualization (bar plots, scatter plots, heatmaps, boxplots)
- Statistical Hypothesis Testing (T-test, One-Way ANOVA)

---

## Key Insights

- Arabica beans consistently score higher and have fewer defects than Robusta.
- Papua New Guinea, Ethiopia, and Japan lead in cup scores.
- Washed/Wet is the most preferred processing method globally.
- Aroma, Flavor, and Aftertaste are highly correlated with overall cup scores.
- Large batch sizes tend to have fewer defects.
- Bean color and altitude showed minimal direct impact on quality.
- Cup quality has gradually declined over the years, especially after 2009.
- Hypothesis testing confirmed significant differences in quality across species, varieties, and countries.

---

## Hypothesis Testing

1. **T-Test**: Arabica vs Robusta (Cup Points)  
   - Result: Arabica has significantly higher average cup points

2. **ANOVA**: Variety vs Total Defects  
   - Result: Defect levels differ across coffee varieties

3. **ANOVA**: Country of Origin vs Cup Points  
   - Result: Cup quality varies significantly across countries

---

## Conclusion

The project confirms that species type, country of origin, and certain processing methods have a measurable effect on coffee quality. Arabica stands out as the top-performing species, and attributes like aroma and flavor are reliable indicators of high cup scores. This analysis helps producers and buyers focus on key factors that drive coffee quality.

---

## Future Recommendations

- Apply machine learning to predict cup scores from features
- Analyze weather, soil, and geographic data for deeper insights
- Track changes in quality and defects across time for specific farms
- Develop a dashboard to monitor coffee quality metrics interactively
- Expand analysis with consumer reviews or pricing data

---

## Author

This project was completed using Python for educational and analytical purposes.  
Contributions, suggestions, or feedback are welcome.


#  Analysis and Prediction of Maternal Mortality Rate using a Statistical Model



### A Critical Health Challenge

Maternal mortality has long been a major concern for national health services.  
It is defined as the death of a woman during pregnancy, childbirth, or within 42 days of termination of pregnancy, regardless of the duration and location of the pregnancy.

### Why This Matters

Every year, thousands of women lose their lives due to preventable complications.  
Understanding and predicting maternal mortality is crucial for implementing effective and timely interventions.

---

## Factors Influencing Maternal Mortality

This project investigates the association between maternal mortality and the following variables:
- GDP per capita
- Health expenditure
- Skilled birth attendance
- Access to healthcare
- Geographical region
- Year (temporal trends)

---

## Methodology

1. **Data Cleaning & Transformation**  
   Using `dplyr`, `tidyr`, and `lubridate` to prepare the data for analysis.

2. **Exploratory Data Analysis (EDA)**  
   - Time series visualization  
   - Correlation matrices  
   - Heatmaps and maps  
   - Trend plots

3. **Regression Modeling**  
   Linear regression and multivariate regression models were applied to identify associations and predictive factors.
`

---

## Data Description

The dataset includes the following columns:
| Variable                     | Description                                         |
|-----------------------------|-----------------------------------------------------|
| Country                     | Name of the country                                 |
| Year                        | Year of observation                                 |
| Maternal Mortality Rate     | Number of maternal deaths per 100,000 live births   |
| GDP per capita              | Economic indicator in USD                           |
| Health expenditure (% GDP)  | Total health spending relative to GDP               |
| Skilled Birth Attendance    | Percentage of births attended by skilled personnel  |

---

## Results: Trend of maternal mortality
Screenshot from 2025-03-17 12-54-01.png



---

##  Conclusion

- Maternal mortality is significantly associated with GDP per capita, healthcare expenditure, and access to skilled birth attendance.
- Higher economic development and better health systems correlate with lower MMR.
- Mapping reveals strong geographical disparities in maternal health.

---

## 📚 References

1. World Bank Dataset on Maternal Mortality  
2. WHO Health Statistics 2017  
3. UN SDG Reports  


---




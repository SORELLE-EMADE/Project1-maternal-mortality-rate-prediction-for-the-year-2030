# Project1-maternal-mortality-rate-prediction-for-the-year-2030
# 📘 Maternal Mortality Rate Analysis in R

## 📌 Project Title
**Exploratory and Causal Analysis of Maternal Mortality Rate**

---

## 📖 Description

This project aims to analyze the **Maternal Mortality Rate (MMR)** using statistical and visual techniques in **R**. The objective is to explore temporal and geographical trends in MMR, and identify potential relationships with other indicators such as GDP and health expenditure. The analysis includes:
- Data wrangling and cleaning
- Time series visualization
- Geographical mapping
- Correlation and regression analysis

---

## 🧰 Technologies Used

- **R**
- **RMarkdown**
- `ggplot2` for data visualization  
- `dplyr`, `tidyr` for data manipulation  
- `readr`, `lubridate`, `scales`, `broom`  
- `rworldmap` for geographical plotting  

---

## 📂 Files

- `maternal_mortality_rate.Rmd` – Main R Markdown file containing code and explanations  
- `figures/` – Folder where generated plots and maps are stored  
- `data/` – (Optional) Folder containing datasets used in the analysis  

---

## ▶️ How to Run

1. Open `maternal_mortality_rate.Rmd` in **RStudio**.
2. Click **Knit** to produce the report (HTML or PDF).
3. Make sure to install the required packages if not already available:
```r
install.packages(c("tidyverse", "lubridate", "rworldmap", "broom"))


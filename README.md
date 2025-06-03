## 🌍 World Happiness Report - Data Mining & Visualization (R)

This project focuses on analyzing the **World Happiness Report** using R for data wrangling, exploratory data analysis, and insightful visualizations. It investigates how factors like GDP, social support, and freedom affect happiness across different countries and continents.

---

### 🎯 Main Objectives

* Import and clean World Happiness datasets
* Handle missing data and unify column structures
* Create visual comparisons across continents and economic indicators
* Identify which variables most strongly correlate with happiness
* Explore the relationship between happiness and perceptions of government, generosity, life expectancy, and more

---

### 🧾 Dataset Description

The dataset includes:

* **Country-wise Happiness Scores**
* Features such as:

  * `Logged GDP per capita`
  * `Social support`
  * `Healthy life expectancy`
  * `Freedom to make life choices`
  * `Generosity`
  * `Perceptions of corruption`
* Geographic features such as: `country`, `region`

---

### 📊 Key Analysis & Visualizations

* **Missing Data Visualization**
  Used `naniar::gg_miss_upset()` to display missing data patterns.

* **Distribution by Continent**
  Boxplots comparing Happiness Scores across continents.

* **Scatterplots**
  Analyzing the relationship between:

  * GDP vs Happiness
  * Social Support vs Happiness
  * Freedom vs Happiness
  * Healthy Life Expectancy vs Happiness

* **Color-coded Density Plots**
  Highlighting how factors differ by region.

* **Interactive Maps**
  Dynamic maps visualizing Happiness Score and Life Expectancy by country using geographic coordinates.

* **Top 10 & Bottom 10 Countries**
  Identified based on Happiness Score.

* **Correlation Matrix Heatmap**
  To detect strong predictors of happiness.

---

### 📈 Modeling & Insights

* The report shows a **positive correlation** between happiness and:

  * GDP per capita
  * Social support
  * Life expectancy
  * Freedom to make life choices

* **Perception of corruption** showed a negative relationship with happiness.

* **North American and Western European countries** ranked highest in overall happiness.

* **Sub-Saharan Africa and South Asia** had the lowest scores, mostly influenced by low GDP and weaker social support systems.

---

### 🛠️ Tools & Libraries Used

* **R and RMarkdown**
* `dplyr`, `tidyr`, `ggplot2`, `naniar`, `corrplot`, `gridExtra`, `readxl`, `stringr`, `ggthemes`, and others.

---

### 📌 Conclusion

This analysis provides clear evidence that happiness is strongly influenced by both economic and social indicators. Countries with high GDP, stronger social support systems, and more freedom tend to score higher in happiness rankings. The visualizations effectively illustrate global disparities and serve as a powerful tool for policymakers aiming to improve quality of life.

---

### 👥 Group Members
* Natasha Kayla Cahyadi
* Caroline Christovani Odilia

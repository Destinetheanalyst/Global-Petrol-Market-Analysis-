<img width="800" height="741" alt="Descriptive Analysis" src="https://github.com/user-attachments/assets/358da729-a377-4c03-985d-ff573c8df1fa" />
# 🌍 Global Petrol Market Analysis  
### Descriptive · Statistical · Predictive Analytics

---

## 📌 Project Overview

This project explores global petrol pricing and oil consumption patterns across **181 countries** using Python-based data analytics techniques.

The objective is to:
- Understand **global fuel price distribution**
- Identify **key economic and policy drivers**
- Build **predictive models** for petrol pricing behavior

The analysis is structured into:
- **Descriptive Analytics** → What is happening?
- **Statistical Analytics** → Why is it happening?
- **Predictive Analytics** → What could happen next?

---

## 📊 Dataset Information

- **Dataset**: Petrol Dataset (June 20, 2022)  
- **Coverage**: 181 Countries  

### Key Variables:
- Daily Oil Consumption (Barrels)
- Petrol Price per Litre (USD)
- Petrol Price per Gallon (USD)
- Yearly Consumption per Capita (Gallons)
- World Share (%)

---

## 🛠️ Tools & Technologies

- **Python 3**
- **pandas** → Data manipulation  
- **scikit-learn** → Machine learning  
- **matplotlib** → Visualization  
- **scipy** → Statistical analysis  

---

## 🔍 1. Descriptive Analytics

### 🌎 Key Insights

- 🇺🇸 United States leads global oil consumption (~19.7M barrels/day)
- 🌍 Global average petrol price: **$1.51/L**
- 📉 Cheapest petrol: **Venezuela ($0.02/L)**
- 📈 Most expensive petrol: **North Korea ($14.50/L)**

### 📊 Distribution Analysis

- Petrol prices are **right-skewed**
- Mean > Median → influenced by high-price outliers
- Majority of countries pay **below global average**

### ⛽ Consumption Patterns

- Top 5 countries consume **over 50% of global oil**
- Per capita consumption:
  - Median: **180 gallons/year**
  - Range: **2 – 3680 gallons**

<img width="800" height="741" alt="Descriptive Analysis" src="https://github.com/user-attachments/assets/e14dc081-b453-433c-aac3-bfe94ccb37fa" />
---

## 📈 2. Statistical Analytics

### 🔗 Correlation Analysis

- Perfect correlation:
  - Price per Gallon ↔ Price per Litre (**r = 1.00**)
- Weak relationship:
  - Consumption vs Price (**r ≈ -0.03**)

### ⚠️ Outlier Detection

- Method: **Z-score (|z| > 2)**
- Identified **2 extreme countries**
- Driven by:
  - Subsidies (ultra-low prices)
  - Import dependency (very high prices)

### 📉 Regression Insights

**Per Capita vs Price**
- R² = **0.003** → negligible predictive power

**Consumption vs Price**
- No strong linear relationship observed

### 📊 Quartile Analysis

| Metric | Value |
|------|------|
| Q1 | $1.10 |
| Median | $1.40 |
| Q3 | $1.79 |

Most countries fall within this band.


<img width="840" height="779" alt="Statistical Analysis" src="https://github.com/user-attachments/assets/ef9ea314-dcf0-488b-aeaa-84db864516ba" />

---

## 🤖 3. Predictive Analytics

### 🧠 Clustering (K-Means, k=4)

Countries segmented into:

- Heavy Consumers  
- High Price / Low Volume  
- Efficient & Affordable  
- Mid-Tier Economies  

📌 **Insight**: A small number of countries dominate global oil consumption.

---

### 📈 Polynomial Regression

- Model: Degree-2 Polynomial  
- R² = **0.002**

Findings:
- Slight non-linear relationship
- Higher consumption → lower price (initial trend)

---

### 📉 Model Performance

- RMSE ≈ **0.743 USD/L**
- Struggles with:
  - Extremely cheap countries
  - Extremely expensive countries

---

### 🧩 Multi-Feature Regression

**Features Used:**
- Consumption
- World Share
- Per Capita Usage

**Performance:**
- R² = **0.009**

**Key Insight:**
- Daily oil consumption has the **strongest negative influence on price**

---

### 🔮 Scenario Simulation

- Increasing global oil share → **lower petrol prices**

Indicates:
- Economic leverage  
- Domestic production advantage  
- Strong policy influence  


<img width="850" height="760" alt="Predictive Analysis" src="https://github.com/user-attachments/assets/2c20cd61-c925-4344-9da0-987d212c0d0d" />

---

## 📊 Key Findings Summary

| Metric | Value |
|------|------|
| Countries Analyzed | 181 |
| Avg Price/Litre | $1.51 |
| Cheapest Country | Venezuela ($0.02) |
| Most Expensive | North Korea ($14.50) |
| Price Range | 660x difference |
| Top Consumer | United States |
| Clusters Identified | 4 |
| Best Model R² | 0.009 |

---

## 💡 Strategic Insights

- High-consumption countries often enjoy **lower fuel prices**
- Petrol prices are strongly influenced by:
  - Government subsidies  
  - Tax policies  
  - Domestic production capacity  

- Simple models perform poorly → **multi-factor modeling is required**
- Global fuel economics is **policy-driven, not purely market-driven**

---

## 🚀 Future Improvements

- Integrate:
  - Tax rates  
  - Subsidy data  
  - Refinery capacity  

- Deploy model as an **API**
- Build **interactive dashboards** (Power BI / Streamlit)
- Implement **real-time prediction systems**

---

## 📁 petrol-analysis/
│
├── data/
│   └── Petrol_Dataset_June_20_2022.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── visuals/
│   └── charts.png
│
├── models/
│   └── regression_models.pkl
│
└── README.md


---

## 👤 Author

**Dike Nnaemeka Destine**

- 🔗 GitHub: https://www.github.com/Destinetheanalyst  
- 🔗 LinkedIn: https://www.linkedin.com/in/nnaemeka-destine-dike-9a27b531a/  

---

## ⭐️ If you found this useful

Give this repo a ⭐️ and share it with others in data science!

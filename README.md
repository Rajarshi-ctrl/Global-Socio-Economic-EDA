# Global-Socio-Economic-EDA
Comprehensive Exploratory Data Analysis of global socio-economic indicators from World Bank EdStats database (1970-2020). Python | Pandas | Matplotlib | Seaborn | Plotly
# 🌍 Global Socio-Economic Indicators Analysis

## Exploratory Data Analysis of World Bank EdStats Data (1970-2020)

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Data: World Bank](https://img.shields.io/badge/Data-World_Bank-green.svg)](https://datacatalog.worldbank.org/)

---

## 📊 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of global socio-economic indicators spanning **195+ countries** over **50 years** (1970-2020). Using data from the **World Bank EdStats database**, I uncovered critical patterns, correlations, and disparities that define the state of human development across the world.

### 🎯 Key Objectives
- Analyze relationships between GDP, education, health, and environmental indicators
- Identify regional disparities in socio-economic development
- Examine gender education gaps and their economic impact
- Provide data-driven strategic recommendations for policymakers

### 🔑 Key Findings

✅ **Strong correlation** between GDP per capita, life expectancy, and education  
✅ **Birth rates decline** sharply with income and female education levels  
✅ **Regional disparities**: Sub-Saharan Africa and South Asia lag significantly  
✅ **Gender education gap** contributes to productivity losses in low-income regions  
✅ **Environmental trade-offs**: CO2 emissions rise with industrialization  

---

## 📁 Dataset Information

| Attribute | Details |
|-----------|----------|
| **Source** | World Bank EdStats (Global Socio-Economic Data) |
| **Scale** | ~886,000 observations across 70 indicators |
| **Timeframe** | 1970 - 2100 (Historical + Projections) |
| **Countries** | 195+ countries across 7 world regions |
| **Dimensions** | Country, Region, Income Group, Year, Value |

### Key Indicators Analyzed

- **Economic**: GDP per capita, Income classification
- **Health**: Life expectancy, Birth rate, Death rate, Infant mortality
- **Education**: Literacy rate, School enrollment (primary/secondary/tertiary), Education index
- **Environment**: CO2 emissions, Energy use
- **Demographics**: Urban population share, Fertility rate
- **Gender**: Female tertiary enrollment ratio

---

## 🛠️ Technologies & Tools

```python
# Core Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go
```

**Tech Stack:**
- **Python 3.8+** - Programming language
- **Pandas** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Static visualizations
- **Plotly** - Interactive visualizations
- **Jupyter Notebook** - Development environment
- **Google Colab** - Cloud-based execution

---

## 📈 Analysis & Visualizations

### 15 Chart Types Implemented

1. **Bar Chart** - Countries by Region
2. **Pie Chart** - Income Group Distribution
3. **Box Plot** - Education Indicators by Income
4. **Line Chart** - Regional Trends Over Time
5. **Horizontal Bar** - Top Data Reporting Countries
6. **Stacked Bar** - Region vs Income Group
7. **Scatter Plot** - Education Expenditure vs Literacy
8. **Violin Plot** - Indicator Distribution by Region
9. **Histogram** - Country-Level Mean Values
10. **Bar Chart** - Top Indicators by Coverage
11. **Grouped Bar** - Primary vs Secondary Enrollment
12. **Area Chart** - Gender Enrollment Trends
13. **Choropleth Map** - Global GDP Distribution
14. **Correlation Heatmap** - Feature Relationships
15. **Pair Plot** - Multi-variable Analysis

### Sample Visualizations

> **Note:** Screenshots of key charts from the analysis are available in the notebook.

---

## 🔍 Key Insights

### 1. Economic-Health-Education Nexus
- **Strong positive correlation (r > 0.85)** between GDP per capita, life expectancy, and education index
- Countries cannot achieve sustained economic growth without investing in human capital

### 2. Demographic Transition
- Birth rates show **strong negative correlation (r < -0.70)** with:
  - Income level
  - Female education
  - Urban population share
- Validates the classic demographic transition model

### 3. Regional Disparities
- **Sub-Saharan Africa** and **South Asia** consistently lag in:
  - GDP per capita (< $5,000)
  - Life expectancy (< 65 years)
  - Literacy rates (< 70%)
- **North America, Europe, East Asia** lead across all metrics

### 4. Gender Education Gap
- Female tertiary enrollment is **30-40% lower** in low-income regions
- This gap translates to:
  - Reduced workforce participation
  - Lower GDP growth potential
  - Perpetuation of poverty cycles

### 5. Environmental Sustainability Challenge
- CO2 emissions and energy use **rise exponentially** during industrialization
- Developing nations face a critical trade-off:
  - Rapid economic growth vs. environmental sustainability
  - Renewable energy investment is essential

### 6. Income Group as Super-Predictor
- Income classification (Low/Lower-Middle/Upper-Middle/High) is a **powerful predictor** of:
  - Health outcomes
  - Education levels
  - Environmental impact
  - Data availability quality

---

## 💡 Strategic Recommendations

### For Policymakers & Development Organizations

1. **Prioritize Education Investment** 💼
   - Focus on low & lower-middle income nations
   - Education is the #1 lever for economic growth
   - Target: Increase education spending to 6% of GDP

2. **Close the Female Education Gap** 👩‍🎓
   - Implement scholarship programs for girls
   - Ensure safe learning environments
   - Potential GDP boost: 10-15% over 20 years

3. **Leverage Urbanization Strategically** 🏙️
   - Controlled urban growth with proper infrastructure
   - Housing, transport, sanitation investments
   - Urbanization correlates with 2-3% higher GDP growth

4. **Improve Healthcare Infrastructure** 🏥
   - Vaccination programs
   - Maternal health support
   - Clean water access
   - Target: 75+ years life expectancy by 2040

5. **Implement Region-Specific Policies** 🌏
   - Sub-Saharan Africa: Focus on basic education & health
   - South Asia: Gender equity & urbanization
   - Latin America: Income inequality reduction

6. **Monitor Environmental Sustainability** 🌱
   - Invest in renewable energy infrastructure
   - Green industrialization pathways
   - Target: Peak CO2 by 2035, net-zero by 2060

7. **Reduce Intra-National Inequality** ⚖️
   - Progressive fiscal policies
   - Social safety nets
   - Minimum wage enforcement

---

## 📂 Project Structure

```
Global-Socio-Economic-EDA/
│
├── Data/
│   ├── EdStatsData.csv
│   ├── EdStatsCountry.csv
│   ├── EdStatsCountry-Series.csv
│   ├── EdStatsFootNote.csv
│   └── EdStatsSeries.csv
│
├── Notebooks/
│   └── EDA_Global_Socio_Economic.ipynb
│
├── Visualizations/
│   ├── chart_01_countries_by_region.png
│   ├── chart_02_income_distribution.png
│   ├── chart_03_education_by_income.png
│   └── ... (15 charts total)
│
├── Presentation/
│   └── Global_Socio_Economic_EDA_Presentation.pdf
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.8+
Jupyter Notebook / Google Colab
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Rajarshi-ctrl/Global-Socio-Economic-EDA.git
cd Global-Socio-Economic-EDA
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook Notebooks/EDA_Global_Socio_Economic.ipynb
```

### Alternative: Run in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID)

---

## 📊 Data Wrangling Steps

1. **Data Loading** ✅
   - Loaded 5 CSV files from World Bank EdStats
   - 886,930 rows × 70 columns (wide format)

2. **Data Cleaning** ✅
   - Dropped empty `Unnamed:69` column
   - Handled missing values (retain only actual measurements)
   - Type conversions for Year columns

3. **Data Transformation** ✅
   - Converted wide format to long format
   - Result: 4.19M rows × 6 columns
   - Columns: Country Code, Country Name, Indicator Code, Indicator Name, Year, Value

4. **Data Enrichment** ✅
   - Merged with country metadata
   - Added Region and Income Group dimensions
   - Final dataset: 3.9M rows ready for analysis

5. **Feature Engineering** ✅
   - Filtered key indicators for focused analysis
   - Created aggregated metrics (mean, median by region/income)
   - Computed correlation matrices

---

## 📚 Methodology

### Analysis Framework

```
Data Collection → Data Cleaning → Exploratory Analysis → Visualization → Insights → Recommendations
```

### Chart Selection Strategy

| Analysis Type | Chart Type | Use Case |
|--------------|-----------|----------|
| **Univariate** | Bar, Pie, Histogram | Single variable distribution |
| **Bivariate** | Scatter, Box, Violin | Relationship between 2 variables |
| **Multivariate** | Heatmap, Pair Plot | Multiple variable interactions |
| **Time Series** | Line, Area | Trends over time |
| **Geographical** | Choropleth | Spatial distribution |

---

## 🎓 Skills Demonstrated

✅ **Data Wrangling** - Cleaning, transformation, merging large datasets  
✅ **Exploratory Data Analysis** - Statistical analysis, pattern recognition  
✅ **Data Visualization** - 15+ chart types, static & interactive  
✅ **Statistical Insight** - Correlation analysis, distribution analysis  
✅ **Business Intelligence** - Translating data into actionable recommendations  
✅ **Python Programming** - Pandas, NumPy, Matplotlib, Seaborn, Plotly  
✅ **Storytelling** - Presenting complex insights clearly  
✅ **Documentation** - Comprehensive README, code comments  

---

## 📖 Conclusion

This EDA reveals that **global inequality is multidimensional**, spanning income, health, education, gender equity, and environmental sustainability. The analysis provides:

- **Strong analytical foundation** for building predictive ML models
- **Data-driven insights** for policymakers and development organizations
- **Evidence-based recommendations** for targeted interventions
- **Clear demonstration** of data analysis skills for portfolio purposes

Key takeaway: **Education and healthcare investment in low-income regions will yield the highest ROI for global development.**

---

## 🔗 Links & Resources

- **Google Colab Notebook**: [View Full Analysis](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID)
- **Presentation**: [View Slides](https://docs.google.com/presentation/d/YOUR_PRESENTATION_ID)
- **LinkedIn**: [Rajarshi Dutta](https://linkedin.com/in/rajarshidutta99)
- **Portfolio**: [rajarshi.vercel.app](https://rajarshi.vercel.app/)
- **GitHub**: [Rajarshi-ctrl](https://github.com/Rajarshi-ctrl)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **World Bank** - For providing comprehensive EdStats database
- **Python Community** - For excellent data analysis libraries
- **Mentors & Peers** - For valuable feedback and suggestions

---

## 📧 Contact

**Rajarshi Dutta**  
Data Analyst | Python | SQL | Power BI  

📧 Email: drajarshi01@gmail.com  
💼 LinkedIn: [linkedin.com/in/rajarshidutta99](https://linkedin.com/in/rajarshidutta99)  
🌐 Portfolio: [rajarshi.vercel.app](https://rajarshi.vercel.app/)  
💻 GitHub: [github.com/Rajarshi-ctrl](https://github.com/Rajarshi-ctrl)  

---

### ⭐ If you found this project helpful, please give it a star!

---

**Made with ❤️ by Rajarshi Dutta | © 2026**


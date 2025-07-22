
# Rice Cultivation Yield Analysis Project

## Overview

This project analyzes farm-level rice cultivation data to understand patterns in agronomic practices and their impact on yield outcomes. By performing detailed exploratory data analysis (EDA), the goal is to provide data-driven recommendations to support farmer advisory services and improve productivity.

## 🎯 Project Objectives

1. **Descriptive Profiling** of rice farming practices across surveyed farmers.
2. **Identify Patterns and Trends** in yield outcomes based on:
   - Farm size
   - Soil type
   - Fertilizer use
   - Irrigation frequency
   - Pest management
   - Other management variables
3. **Subgroup Comparison** of yield and input use by:
   - District
   - Landholding size
   - Irrigation count
4. **Document Challenges** in data quality and collection.
5. **Generate Recommendations** for agricultural extension agents and program design teams.

## Research Questions

- What are the most common agronomic practices (e.g., fertilizer use, irrigation, pest control)?
- How does yield vary by:
  - Farm size
  - Input application
  - Irrigation frequency
  - Management methods
- Are there trends associated with specific practices (e.g., organic manure, basal fertilizer)?
- How do practices differ by:
  - Region
  - Soil type
  - Irrigation access?
- What are the major data quality issues affecting evaluation?

##  Data Description

- **Size**: 23,000 and above farm-level observations  
- **Variables**: >40, across major categories:
  - **Farm Info**: land size, tillage, soil type, drainage class
  - **Input Use**: fertilizer types and quantities (Urea, DAP, SSP, NPKS, Zinc), organic inputs
  - **Crop Management**: transplant date, nursery management, irrigation frequency, pest control
  - **Harvest**: harvest method, timing
  - **Extension Exposure**: use of digital scorecards, videos, geo-fencing
  - **Outcome**: rice yield in kilograms

### ✅ 1. Data Cleaning
- Missing values handled
- Data types corrected
- Outliers reviewed

### ✅ 2. Exploratory Data Analysis (EDA)
- **Descriptive Statistics** for numeric & categorical variables
- **Visualizations**:
  - Yield vs. Land Size
  - Yield by Soil Type, Fertilizer Use, Irrigation
  - Input usage frequency
- **Comparative Analysis** across subgroups
- **Pivot Tables** & **Correlation Heatmaps**
- **ANOVA** and **T-tests** on:
  - Disease Type
  - Fertilizer Use
  - Weeding Frequency
  - Irrigation Access
- **Trend Exploration** (e.g., organic fertilizer impact, harvest method, seedling age)

##  Key Insights

- Yield is significantly influenced by **irrigation**, **weeding frequency**, and **harvest method**.
- **Drainage class** and **soil type** also show strong relationships with yield outcomes.
- Some variables (e.g., organic pesticide use) do **not show significant impact** on yield.
- **Data quality issues** (e.g., inconsistent units, missing land sizes) are noted in select fields.

##  Recommendations

- **Target low-yield districts** for additional support and intervention.
- **Optimize irrigation and fertilizer application frequency** through training and extension.
- Encourage use of **best-performing practices**, e.g., optimal weeding and harvest methods.
- Address **data collection gaps** and ensure consistency across enumerators and regions.

## Deliverables

| Deliverable                     | Status     |
|--------------------------------|------------|
| Cleaned dataset                | ✅ Done     |
| EDA report                     | ✅ Done     |
| Agronomic trends summary       | ✅ Done     |
| Extension recommendations      | ✅ Drafted  |
| Dashboard for field use        | In Progress |

## 🔧 Tools & Technologies

- **Python (Pandas, Plotly, Seaborn, SciPy)**
- **Jupyter Notebooks / Quarto**
- **Visualizations with Plotly Express**
- **Statistical Tests** (ANOVA, T-tests, Correlation)
- **CSV Dataset** (23,000 observations)


## we are having 4 different folders 
- notebook: contains all python code of what we have done.
- data : Has both row data and processed data
- results: cantain some outputed visual images
- docs : Has prestantion file and project description and task
## Authors

- **Ashura**
- **Claudine**
- **Delphine**
- **Jedid jah**

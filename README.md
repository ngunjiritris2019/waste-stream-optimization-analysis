# Waste Stream Optimization Dashboard: 7-Category Segregation Analysis

## Project Overview
This project analyzes 18 months of waste management operations data (March 2024 - September 2025) from a waste segregation facility in Tanzania. The analysis focuses on 7 major waste categories to identify operational patterns, seasonal trends, and provide data-driven forecasts for capacity planning.

## Business Problem
Waste management facilities need to:
- Understand waste composition to optimize segregation processes
- Identify seasonal patterns for resource allocation
- Forecast future volumes for capacity planning
- Track year-over-year growth and operational efficiency

## Technical Stack
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **matplotlib & seaborn** - Data visualization
- **numpy** - Numerical operations
- **scipy** - Statistical analysis and forecasting

## Dataset
- **Time Period:** March 2024 - September 2025 (18 months)
- **Records:** Daily waste collection data
- **Categories:** 7 major waste streams
  - PET Plastics
  - Hard Plastics
  - Flexible Plastics
  - Metals & Cans
  - Paper
  - Glass
  - Organics

##   Analysis Components

### 1. Data Cleaning & Preprocessing
- Handled mixed data types (object to numeric conversion)
- Managed missing values and zero-collection days
- Created temporal features (month, year, weekly patterns)
- Aggregated daily data to monthly summaries

### 2. Exploratory Data Analysis
- Overall waste composition analysis
- Category-wise distribution and percentages
- Temporal trend identification
- Seasonal pattern recognition

### 3. Key Visualizations
1. **Waste Composition Pie Chart** - Overall category distribution
2. **Monthly Trends Line Chart** - All categories over 20 months
3. **Top 3 Categories Focused View** - Cleaner trend visualization
4. **Seasonal Patterns** - Average daily collection by month
5. **Year-over-Year Comparison** - 2024 vs 2025 performance
6. **Growth Analysis** - Total waste trend and month-over-month growth rates

### 4. Forecasting
- Linear regression-based trend analysis
- 3-month forward projection
- Moving average smoothing for trend identification

## Key Findings

### Operational Insights
- Identified dominant waste category accounting for largest volume share
- Tracked operational stability through coefficient of variation analysis
- Documented active collection patterns across the analysis period


### Growth Metrics
- Calculated year-over-year growth trends
- Identified highest and lowest performing months
- Forecasted next quarter volumes with confidence intervals
  

##  Business Value
This analysis provides:
- **Data-driven decision making** for operations management
- **Predictive insights** for capacity planning
- **Performance tracking** through year-over-year comparisons
- **Cost optimization** opportunities through category focus
- **Sustainability metrics** for circular economy reporting

##  How to Run This Project

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### Execution
1. Clone this repository
2. Place your data file in the project directory
3. Open `waste_analysis.ipynb` in Jupyter Notebook
4. Run all cells sequentially

## Project Structure
```
Waste_Stream_Analysis/
│
├── waste_analysis.ipynb          # Main analysis notebook
├── Waste Categories Data.csv     # Raw data (not included for confidentiality)
├── README.md                      # Project documentation
```

## Skills Demonstrated
- **Data Wrangling:** Cleaning messy real-world data with mixed types
- **Time Series Analysis:** Trend identification, seasonality detection
- **Statistical Modeling:** Linear regression, forecasting
- **Data Visualization:** Creating professional, publication-ready charts
- **Business Intelligence:** Translating data into actionable insights
- **Domain Knowledge:** Understanding circular economy and waste management operations

## Contact
**Name: Beatrice Ngunjiri**
- LinkedIn: https://www.linkedin.com/in/beatrice-ngunjiri-41775b1b1/
- Email: ngunjiritris@gmail.com

## 📝 License
This project is for portfolio demonstration purposes. Data has been anonymized to protect business confidentiality.

---

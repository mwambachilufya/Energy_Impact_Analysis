# Energy_Impact_Analysis
Data Analytics project that investigates the effect of energy consumption by the mines on the Copper mining operations in Zambia from 2014 to 2024
# Key Findings

- **Weak Negative Correlation**: Only 9.19% of variance in copper production is explained by electricity consumption. With a correlation coefficient of -0.303210035.
- Whereas it is the expectation that the more copper Zambia produces the more electricity is consumed for such operational processes this analysis seems to suggest otherwise. Significantly, in 2024 when Zambia was experiencing an energy crisis due to drought, electricity consumption by the mining sector was at 4650 GWh( the lowest in a 10 year period) but copper production was at 820,000 tonnes the second best it has been over an eleven year period where the best production was in 2020 at 828,000 tonnes. This relationship is quite common across this time period.
# Contents of this repository

- `Energy impact project.xlsx` - Raw data including yearly production, consumption, rainfall, and temperature metrics
- `Dashboard.twb` - Interactive Tableau dashboard
- `dashboard screenshot.png` -  a screenshot of the Dashboard visualization
- `README.md` - Project documentation

## Tools used

- **Microsoft Excel**: Data cleaning, descriptive statistics, regression analysis, Z-score calculations
- **Tableau Public**: Creating the dashboard.

## 📈 Dashboard Components

### 1. Z-Score Analysis (Efficiency Tracking)
- Visualizes standardized production and consumption metrics over time
- Identifies periods of high efficiency vs. operational waste
- Reference lines at average (Z = 0) for quick comparison
![Z Score Analysis](Z%20Score%20analysis.png)
*Z-Score analysis showing efficiency trends and operational patterns (2014-2024)*




### 2. Scatter Plot with Regression
- Shows relationship between electricity consumption and copper production
- Displays weak negative trend line (r = -0.303)
- Highlights the lack of strong linear relationship

### 3. Trend Analysis
- Moving averages smooth year-to-year volatility
- Reveals long-term production patterns
- Shows recent decline in both metrics

## 🔍 Methodology

1. **Data Collection**: Mining operations data (2014-2024) including production volumes, electricity consumption, rainfall, and temperature
2. **Descriptive Statistics**: Mean, median, standard deviation, range calculations
3. **Trend Analysis**: Year-on-year growth rates and CAGR
4. **Standardization**: Z-score calculations to identify outliers and efficiency patterns
5. **Regression Analysis**: Linear regression to quantify relationship strength
6. **Visualization**: Multi-chart dashboard for comprehensive insight communication

## 💡 Insights & Recommendations

### Current State
The weak correlation indicates that **electricity consumption is not a primary driver** of copper production levels. Other operational factors have stronger influence.

### Recommended Next Steps
1. **Expand the model**: Include ore grade quality, equipment age, and maintenance schedules
2. **Environmental factors**: Analyze rainfall and temperature impact on pit accessibility
3. **Operational efficiency**: Investigate the 2023-2024 decline through qualitative analysis
4. **Predictive modeling**: Build multi-variable regression with expanded dataset

## 📊 Data Sources

- Mining operations historical records (2014-2024)
- Variables: Production volume, electricity consumption, generation sent out, rainfall, temperature

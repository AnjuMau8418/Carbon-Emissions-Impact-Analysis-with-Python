# 🌍 Carbon Emissions Impact Analysis with Python

## 📖 Introduction
This project analyzes the impact of carbon emissions on global temperatures by exploring historical trends, detecting anomalies, and simulating future scenarios based on CO₂ concentrations and temperature anomalies. We gain insights into climate change patterns using Python for data processing and visualization.

---

## 🎯 Objective
The primary objectives of this project are:
- 📊 Analyze the relationship between **CO₂ emissions** and **global temperature anomalies**.
- 🔎 Identify **historical trends** and **anomalies** in temperature changes.
- 🔮 Simulate potential **future climate scenarios** based on emission levels.

---

## 📂 Data Collection
The dataset used in this project consists of:
- 🌡️ **Temperature Data**: Annual temperature anomalies (°C) over decades.
- 🏭 **CO₂ Data**: Monthly global atmospheric CO₂ concentrations (ppm).

---

## 🛠️ Tools & Technologies Used

- 🐍 **Python**: Main programming language for data analysis.  
- ☁️ **Google Colab**: Cloud-based environment for executing the Python notebook.  
- 📊 **Pandas**: Data manipulation and preprocessing.  
- 📈 **Matplotlib & Seaborn**: Data visualization.  
- 📊 **Plotly**: Interactive and dynamic visualizations.  
- 📅 **Datetime**: Handling and manipulating date-time data.  
- 📊 **Scipy Stats**: Statistical analysis and hypothesis testing.  
     - `pearsonr`, `spearmanr`: Correlation analysis.  
- 📈 **Statsmodels**: Statistical modeling and time series analysis.  
     - `grangercausalitytests`: Granger causality testing for time series relationships.  
     - `statsmodels.api as sm`: Advanced statistical modeling.  
- 🤖 **Scikit-learn**: Machine learning models for predictive analysis.  
     - `KMeans`: Clustering analysis.  
     - `StandardScaler`: Feature scaling for machine learning models.  
     - `LinearRegression`: Regression modeling.  
- 🔢 **NumPy**: Numerical computations and array operations.  

---

## 🔬 Methodology

### 📌 Step 1: Data Preprocessing
- 📥 Loaded the dataset using **Pandas**.
- 🛠️ Handled **missing values** and performed **data cleaning**.
- 🔄 Standardized data formats for **consistency**.

### 📌 Step 2: Exploratory Data Analysis (EDA)
- 🏷️ Computed key **statistics** (mean, median, variance) for temperature changes and CO₂ levels.
- 📈 Analyzed trends in **temperature anomalies** over time.
- 🔗 Conducted **correlation analysis** between CO₂ concentrations and temperature changes.

### 📌 Step 3: Data Visualization
- 📊 **Line charts** showing temperature anomalies over decades.
- 🔍 **Scatter plots** illustrating the relationship between CO₂ levels and temperature anomalies.
- 📉 **Histogram distributions** of temperature changes.

### 📌 Step 4: Predictive Modeling
- 🔮 Developed **regression models** to predict future temperature anomalies based on CO₂ levels.

---

## 🔍 Key Findings
- 🚀 **Increasing Trend**: Global temperature anomalies have risen over time, closely following the **rise in CO₂ levels**.
- 🔗 **Strong Correlation**: A significant correlation exists between **atmospheric CO₂ concentrations** and **temperature rise**.
- 📡 **Predictive Insights**: Regression models suggest that **without intervention, temperature anomalies will continue to rise**, impacting global climate patterns.

---

## ✅ Conclusion
This project demonstrates the strong impact of carbon emissions on climate change. The findings can inform climate policies and encourage the adoption of emission-reduction strategies.  

Future work could enhance the analysis by incorporating additional environmental factors, such as **methane emissions** and **deforestation rates**.

---

## 🚀 Future Enhancements
- 🤖 **Machine Learning Models**: Implement **deep learning approaches** for more accurate predictions.
- 📡 **Real-Time Data Integration**: Use **APIs** to fetch **live CO₂ emission** and **temperature data**.
- 📜 **Climate Policy Impact Assessment**: Analyze the effectiveness of **international agreements** on reducing emissions.

---

## 📊 Sample Visualization
<p align="center">
  <h2> Time-series of Temperature Change and CO₂ Concentrations </h2>
  <img src="visualizations/Time-series of Temperature Change and CO₂ Concentrations_20250314_031705.png" width="600">
  <p>The time-series graph shows a consistent increase in CO₂ concentrations (measured in ppm) over the years, which indicates the accumulation of greenhouse gases in the atmosphere. Simultaneously, a slight upward trend in global temperature change suggests that rising CO₂ levels are associated with global warming.</p>
</p>

<p align="center">
  <h2> Correlation Heatmap </h2>
  <img src="visualizations/Correlation Heatmap_20250314_031938.png" width="600">
  <p>The heatmap reveals a strong positive correlation (0.96) between CO₂ concentrations and temperature changes. This statistical relationship reinforces the observation that higher CO₂ levels are closely linked with increasing global temperatures, which highlights the importance of addressing carbon emissions to mitigate climate change.</p>
</p>

<p align="center">
  <h2> Temperature Change vs CO₂ Concentration </h2>
  <img src="visualizations/Temperature Change vs CO₂ Concentration_20250314_032148.png" width="600">
  <p>The scatter plot shows a clear linear trend, where higher CO₂ concentrations correspond to greater temperature changes. This visual evidence underscores the direct relationship between CO₂ emissions and global warming, which provides further support for policies targeting reductions in carbon emissions to combat climate impacts.</p>
</p>

<p align="center">
  <h2> Trends in Temperature Change and CO₂ Concentrations </h2>
  <img src="visualizations/Trends in Temperature Change and CO₂ Concentrations_20250314_032326.png" width="600">
  <p>The graph shows the linear trends in both temperature change and CO₂ concentrations over time, represented by their respective slopes. The CO₂ trend has a much steeper slope (0.32) compared to temperature (0.03), which indicates a faster rate of increase in CO₂ emissions relative to temperature change. This suggests that while CO₂ levels are rising rapidly, the temperature impact, though slower, is accumulating steadily and may have long-term consequences.</p>
</p>

<p align="center">
  <h2> Seasonal Variations in CO₂ Concentrations </h2>
  <img src="visualizations/Seasonal Variations in CO₂ Concentrations_20250314_032451.png" width="600">
  <p>The above graph highlights the seasonal fluctuations in CO₂ concentrations, which peak during late spring and early summer (around May) and reach the lowest levels in fall (around September). These variations are likely due to natural processes such as plant photosynthesis, which absorbs CO₂ during the growing season, and respiration, which releases CO₂ in the off-season. This seasonal cycle underscores the role of natural carbon sinks in moderating atmospheric CO₂ levels.</p>
</p>

<p align="center">
  <h2> Clustering of Years Based on Climate Patterns </h2>
  <img src="visualizations/Clustering of Years Based on Climate Patterns_20250314_032630.png" width="600">
  <p>The clustering graph segments years into three distinct climate patterns based on CO₂ concentration and temperature change: low CO₂ and temperature (green), moderate CO₂ and temperature (orange), and high CO₂ and temperature (blue). The progression from green to orange and then to blue clusters reflects a clear trend of increasing temperature change corresponding to rising CO₂ levels, effectively illustrating the correlation between greenhouse gas concentrations and global temperature variations.</p>
</p>


## 🌍 Climate Change Analysis Summary
- **Strong Positive Correlation:** Rising CO₂ levels are closely linked to global temperature anomalies.  
- **Faster CO₂ Growth:** CO₂ concentrations are increasing at a faster rate than temperature changes.  
- **Time-Series & Clustering Analysis:** Show clear trends of escalating emissions driving temperature rise.  
- **Seasonal Variations:** Highlight the moderating role of natural carbon sinks.  
- **Lagged Effects:** Current CO₂ levels have the most significant impact on temperature changes.  
- **Simulated Scenarios:** Show that even modest emission reductions can significantly mitigate global warming.  
- **Key Takeaway:** Urgent action and effective climate policies are needed to address global warming.  

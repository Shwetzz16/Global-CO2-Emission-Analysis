🌍 Global CO₂ Emissions Analysis
Exploratory Data Analysis (EDA) & Visualisation Project

This project provides a comprehensive Exploratory Data Analysis (EDA) of global CO₂ emissions across countries and regions over time. The objective is to understand emission patterns, identify major contributors, analyse regional differences, and visualise long-term trends in global carbon output.

The analysis is performed using Python, with a focus on generating clear, simple, and interpretable visualisations suitable for academic or research purposes.

📁 Project Structure
📦 Global-CO2-Emissions-Analysis
│
├── 📄 Global CO2 Emissions.ipynb    # Main analysis notebook
├── 📄 Carbon_(CO2)_Emissions_by_Country.csv   # Dataset used
├── 📄 README.md                     # Project documentation

📊 Dataset Description

The dataset contains annual CO₂ emissions data for multiple countries and regions.
Columns include:

Column Name	Description
Country	Name of the country
Region	Geographic region (e.g., Asia, Europe)
Date	Observation date
Kilotons of CO2	Total CO₂ emissions (in kilotons)
Metric Tons Per Capita	Per-person CO₂ emissions
Year	Extracted from Date for time-series analysis

🧹 Data Cleaning
Before analysis, the following steps were performed:
Converted the Date column into datetime format
Extracted Year for trend analysis
Ensured numeric columns were properly formatted
Checked for missing values
Removed rows with invalid or missing dates

📈 Visualisations Included
This project contains simple, clear visualisations designed to help understand emission trends at multiple levels.
1. Correlation Heatmap
Shows how total CO₂ emissions relate to per-capita emissions.
2. Outlier Detection (IQR) + Boxplot
Identifies extremely high-emission countries and visualises distribution.
3. Country-Level Time-Series Plots
Displays annual emission trends for major countries like:
China
United States
India
4. Region-Wise Emission Trends
Compares total regional emissions over time.
5. Stacked Area Plot
Shows each region’s share of global emissions across years.
6. Top 10 Countries by Emissions
Ranks countries based on total CO₂ output.
7. Regional Boxplot
Compares emission distribution across regions.

💡 Key Insights
A small number of countries (e.g., China, USA, India) contribute a disproportionately large share of global CO₂ emissions.
Asia has seen the highest growth in emissions over time.
Europe shows stabilisation or slight decline.
Strong correlation exists between total emissions and per-capita emissions.
Emission values are highly skewed, with many extreme high outliers.

📝 Conclusion
This EDA highlights global disparities in CO₂ emissions and helps identify where policy interventions may have the highest impact. Regions like Asia are driving global increases, while developed regions like Europe are stabilising. The results reinforce the need for targeted climate strategies focusing on major emitters.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook

▶️ How to Run the Project
Clone the repository:

git clone (https://github.com/Shwetzz16/Global-CO2-Emission-Analysis)

Install dependencies:
pip install pandas numpy matplotlib

Open the notebook:
jupyter notebook "Global CO2 Emissions.ipynb"
Run all cells to reproduce the visualisations.



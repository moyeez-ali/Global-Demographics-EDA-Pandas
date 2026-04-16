# Global Socio-Economic & Demographic Analysis (Pandas Capstone)

## Project Overview
This is my third and final foundational Pandas project, serving as a capstone for my data wrangling and Exploratory Data Analysis (EDA) learning phase. This project analyzes a comprehensive dataset (`Countries.csv`) containing 64 variables across 194 countries. The dataset includes real-world macro-economic indicators (GDP, inflation), demographics (population, life expectancy), and environmental metrics (CO2 emissions, energy access). 

The primary objective of this project is to perform advanced data cleaning, handle missing metrics, group data by regions/continents, and extract high-level global insights.

## Technologies Used
* **Language:** Python 3
* **Libraries:** Pandas, NumPy
* **Environment:** Jupyter Notebook

## Key Analytical Tasks Performed
1. **Data Profiling & Inspection:** Analyzed the structure of a wide dataset (64 columns), identifying data types and observing non-null value distributions across economic and environmental metrics.
2. **Handling Missing Values:** Applied strategic imputation for missing economic indicators (like `central_government_debt_pct_gdp` and `inflation`) and dropped rows where critical geographical identifiers were missing.
3. **Advanced Filtering & Slicing:** Filtered countries based on specific socio-economic thresholds (e.g., High GDP vs. Low GDP, High Life Expectancy).
4. **Data Aggregation & Grouping:** Grouped the data by `continent` and `region` to calculate aggregate metrics such as average `life_expectancy`, total `population`, and average `co2_emissions` per region.
5. **Feature Engineering:** Derived new columns such as population density (Total Population / Land Area) to add deeper demographic insights.

## Potential Business / Analytical Questions Answered
* Which regions have the highest average life expectancy correlated with health expenditure?
* How does GDP compare to unemployment and inflation rates across different continents?
* What is the distribution of renewable energy consumption vs. fossil fuel usage globally?

## How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have Python and Pandas installed (`pip install pandas numpy`).
3. Open the Jupyter Notebook file to review the code and methodology.
4. Run the cells sequentially to see the step-by-step EDA process.

## Author
**Syed Moyeez Ali** *Data Science Student | Aspiring Data Analyst*

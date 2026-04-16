# Global Demographics & Country Analysis (Pandas Capstone)

## Project Overview
This project focuses on advanced data wrangling and Exploratory Data Analysis (EDA) using Pandas. Working with a comprehensive global dataset (Countries.csv containing 194 records and 64 features), the primary objective was to query, filter, and extract meaningful insights regarding global demographics, political leadership, and regional distributions.

## Technologies Used
* **Language:** Python 3
* **Libraries:** Pandas
* **Environment:** Jupyter Notebook

## Key Analytical Tasks Performed
1. **Data Profiling:** Utilized Pandas functions (`.info()`, `.describe()`, `.shape`) to understand the vast structure of the dataset and the distribution of numerical and categorical variables.
2. **Targeted Data Extraction:** Designed specific queries to isolate exact data points, such as finding the capital city of the most populated country or identifying the political leader of the 2nd most populated nation.
3. **Regional Aggregation & Filtering:** Filtered data by specific continents and regions (e.g., Eastern Europe, Africa) to answer granular geographical questions.
4. **Custom Text Processing:** Engineered a custom Python function using `.apply()` to iterate through the official long-form names of countries and accurately count how many contain the word "Republic."
5. **Handling Missing Data Contextually:** Identified and counted records with missing values (NaN) in specific columns, such as finding the exact number of countries with unknown political leaders.

## Analytical Questions Answered
Through data querying, this project provides answers to several global insights, including:
* Which countries have the highest and lowest populations globally, and what are their capital cities?
* Which 5 nations hold the highest global democracy scores?
* How many distinct geographical regions exist in the dataset, and which specific countries fall under Eastern Europe?
* Which country within the African continent has the highest population?
* How many countries officially include the term "Republic" in their long-form name?

## How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have Python and Pandas installed (`pip install pandas`).
3. Open the `countries.ipynb` file using Jupyter Notebook or your preferred IDE.
4. Run the cells sequentially to observe the data exploration and query results.

## Author
**Syed Moyeez Ali** *Data Science Student | Aspiring Data Analyst*

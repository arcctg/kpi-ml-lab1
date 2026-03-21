# Exploratory Data Analysis: Ukrstat & Titanic Datasets

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data_Viz-8CAAE6.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)

## Project Overview
This repository contains two foundational Exploratory Data Analysis (EDA) projects that demonstrate core data manipulation and visualization skills using Python. The tasks focus on extracting insights from real-world and historical datasets.

By utilizing Python's robust data science stack, this project showcases the ability to load, clean, transform, and analyze tabular data to find meaningful patterns and correlations.

## Key Features
* **Data Wrangling & Preprocessing:** Handling missing values, filtering datasets, and preparing data for analysis.
* **Exploratory Data Analysis (EDA):** Computing descriptive statistics to understand the underlying distribution of data points in both datasets.
* **Data Cleaning:** Utilized Regular Expressions to parse and filter only needed data from a big amount of text columns.
* **Economic Data Analysis (Task 1):** Analyzing Ukrainian pricing statistics (`ukrstat_prices.csv`) to identify economic trends and price variations.
* **Survival Analysis (Task 2):** Investigating the classic Titanic dataset to determine the key factors (such as age, gender, and ticket class) that influenced passenger survival rates.

## Technologies Used
* **Language:** Python
* **Data Manipulation:** Pandas
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## Datasets
1. **Ukrstat Prices (`task_1_ukrstat_data.ipynb`):** A custom dataset (`ukrstat_prices.csv`) containing historical pricing statistics from Ukraine. Sourced from [Ukrstat](https://stat.gov.ua/en).
2. **Titanic Survival (`task_2_TitanicSurvival_data.ipynb`):** The standard introductory machine learning dataset used for predicting passenger survival. Sourced from [Vincent Arel-Bundock](https://vincentarelbundock.github.io/Rdatasets/datasets.html).

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/arcctg/exploratory-data-analysis-portfolio.git
   cd exploratory-data-analysis-portfolio
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the required dependencies:**
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   *Open `.ipynb` file in your browser to run the analysis cells.*

## Results and Insights
**Ukrstat Economic Analysis:**
* **Data Cleansing Success:** Successfully parsed complex string values and extracted clean numerical data using Regular Expressions (`re`), enabling accurate statistical analysis.
* **Descriptive Statistics:** Computed central tendencies (mean, median, mode) and dispersion metrics using Python's built-in `statistics` module to understand price distributions across different consumer categories.
* **Pricing Trends:** Identified significant variations and outliers in the pricing of goods and services in Ukraine, providing a clear view of economic fluctuations within the dataset.

**Titanic Survival Analysis:**
* **Demographic Impact:** Confirmed that gender played a role in survival, with women having a higher survival rate than males.
* **Socio-Economic Factors:** Visualizations clearly demonstrated that passenger class correlated with survival probabilities. First-class passengers were more likely to survive than those in third class.
* **Age Distribution:** Analyzed the age demographics of passengers, identifying how age combined with class and gender affected the likelihood of surviving the disaster.

## License
This project is open-source and available under the [MIT License](LICENSE).

# Credit Risk Analysis and Exploratory Data Analysis (EDA)

## Overview

This project performs Exploratory Data Analysis (EDA) on credit risk data to understand the factors that influence loan defaults. The analysis involves data cleaning, data transformation, outlier treatment, and visualization to identify key trends and patterns in the data. The project uses two datasets: `application_data.csv` (containing loan application information) and `previous_application.csv` (containing information about previous loans).

## Functionality

The project performs the following steps:

1.  **Data Loading and Inspection:** Loads the `application_data.csv` and `previous_application.csv` datasets and inspects their structure and content.
2.  **Data Cleaning:**
    *   Identifies and removes columns with a high percentage of missing values.
    *   Removes redundant columns.
    *   Aggregates document-related columns.
    *   Treats missing values in specific columns using appropriate methods (mode or median).
    *   Converts data types for consistency.
    *   Converts negative day values to years.
3.  **Outlier Treatment:** Identifies and treats outliers in numerical columns such as `AMT_INCOME_TOTAL`, `CNT_CHILDREN`, `AMT_CREDIT`, and `YEARS_EMPLOYED`.
4.  **Binning:** Groups continuous variables into discrete intervals to simplify analysis and visualization.
5.  **Univariate Analysis:** Analyzes the distribution of individual variables to identify key trends and patterns.
6.  **Bivariate Analysis:** Examines the relationship between pairs of variables to understand how they interact and influence loan defaults.
7.  **Merging Data:** Merges the application data and previous application data for a more comprehensive analysis.
8.  **Conclusion:** Summarizes the key findings and insights from the EDA.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/git098/Credit-EDA.git
    cd Credit-EDA
    ```

2.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Download the datasets:**

    *   Download the `application_data.csv` and `previous_application.csv` datasets and place them in the same directory as the notebook.
2.  **Run the Jupyter Notebook:**

    *   Open `Credit_EDA.ipynb` using Jupyter Notebook or JupyterLab.
    *   Run the cells in the notebook to perform the credit risk analysis and EDA.

## Requirements

*   Python 3.6+
*   `pandas`
*   `numpy`
*   `matplotlib`
*   `seaborn`

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

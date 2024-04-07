---

# Rice Production Forecasting in India

## Overview
This project focuses on forecasting rice production in India, leveraging historical data spanning from 2004 to 2023. The goal is to provide insightful predictions on rice production across various states and union territories in India, aiding policymakers and stakeholders in making informed decisions.

## Dataset
The dataset encompasses annual rice production quantities from different states and union territories in India. It's structured into two main tables:

- **Table 1**: Contains data from 2004-2005 to 2012-2013.
- **Table 2**: Extends from 2013-2014 to 2022-2023.

Each table lists the rice production in tonnes for every state/union territory, with the last row representing the total production in India for the year.

## Objective
The primary objective is to analyze the dataset to uncover production trends and predict future rice production for the next five years. This analysis aims at identifying states with potential for production increase and aiding strategic agricultural planning.

## Tools and Libraries Used
- **Python 3**: For data manipulation and analysis.
- **Pandas**: For handling dataset operations.
- **Scikit-learn**: For implementing machine learning models.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Jupyter Notebook**: For interactive code execution and result presentation.

## Installation
Ensure you have Python 3 installed on your system. You can then install the required libraries using pip:

```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
```

## Usage
To replicate the analysis and view the predictions, follow these steps:

1. Clone this repository to your local machine.
2. Open your terminal and navigate to the project's directory.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the `Rice_Production_Forecasting_India.ipynb` notebook and execute the cells sequentially.

## Structure
- `data/`: Contains the dataset files used for analysis.
- `Rice_Production_Forecasting_India.ipynb`: Jupyter Notebook containing the analysis and forecasting model.
- `requirements.txt`: Lists all the Python libraries required for the project.

## Model
The forecasting model is built using a time series analysis approach, focusing on state-wise production trends to predict future outputs. The methodology includes data preprocessing, exploratory data analysis (EDA), feature selection, model training, and evaluation.

## Contributing
Contributions to improve the forecasting model or analysis are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

---

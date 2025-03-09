# COVID-19-Exploratory-Data-Analysis-EDA-

## Overview
This project performs an Exploratory Data Analysis (EDA) on a COVID-19 dataset, examining the impact of various factors such as age, gender, and pre-existing conditions on mortality rates. It includes data preprocessing, visualization, statistical tests, and feature correlation analysis.

## Features
- Data cleaning and preprocessing
- Statistical summaries
- Age and gender-based mortality distribution
- Impact of pre-existing conditions (diabetes, cardiovascular disease, obesity, hypertension) on mortality
- Time-series analysis of COVID-19 deaths
- Correlation heatmaps and feature relationships
- Advanced visualizations (violin plots, boxplots, and pair plots)
- Chi-square test for gender-based mortality
- Export of cleaned dataset

## Requirements
To run this project, install the following Python libraries:
```sh
pip install pandas numpy matplotlib seaborn scipy
```

## Dataset
The dataset used in this analysis can be accessed from Kaggle:
[COVID-19 Dataset](https://www.kaggle.com/datasets/meirnizri/covid19-dataset)

## How to Run
1. Place the dataset in the project directory and update the filename in the script.
2. Run the script using:
   ```sh
   python covid_eda.py
   ```
3. The output will include statistical results and a series of visualizations.

## Output
- Statistical insights printed in the console.
- Multiple graphs and charts illustrating trends and correlations.
- A cleaned dataset saved as `cleaned_covid_data.csv` for further analysis.

## Conclusion
This analysis provides insights into how different variables influence COVID-19 mortality. The findings can assist in identifying high-risk groups and understanding the pandemic's progression.

## Author
**Khadija Alizada**

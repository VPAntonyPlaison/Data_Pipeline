# Data Preprocessing Project

## Objective
The main objective of this project is to design and implement a robust data preprocessing system to address common challenges such as missing values, outliers, inconsistent formatting, and noise, enhancing the quality and reliability of data for machine learning.

## Key Components

### Data Exploration
- Explored data features and their unique values.
- Performed statistical analysis.
- Renamed columns for clarity.

### Data Cleaning
- Handled missing and inappropriate values.
- Removed duplicate rows.
- Identified and treated outliers.
- Replaced `0` in the `age` column with `NaN`.
- Treated null values using appropriate measures.

### Data Analysis
- Filtered data with `age > 40` and `salary < 5000`.
- Plotted age vs. salary.
- Visualized the count of people from each place.

### Data Encoding
- Converted categorical variables into numerical representations using one-hot encoding and label encoding.

### Feature Scaling
- Scaled features using `Standard Scaler` and `Min Max Scaler`.

## Files
- `data_preprocessing.py`: Contains code for data preprocessing.
- `data_analysis.py`: Contains code for data analysis and visualization.
- `README.md`: This file with project details and instructions.


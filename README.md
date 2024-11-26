# Movie Rating Prediction

This project focuses on predicting movie scores (audienceScore and tomatoMeter) using machine learning. The project incorporates preprocessing, modeling, and visualization to derive insights from the data.

---

## Project Overview

**Goal**  
Develop a regression model to predict:
- Audience scores (`audienceScore`)  
- Critic scores (`tomatoMeter`)

**Dataset Features**
- Includes movie-related data such as `director`, `writer`, `genre`, and scores.
- Preprocessing steps like encoding categorical variables and generating smoothed means were used to improve predictions.

**Tools**
- **Python**: Preprocessing, training models, and exporting predictions.
- **Power BI**: Visualization and analysis of results.
- **Libraries**: Pandas, NumPy, Scikit-learn.

---

## Key Features

### 1. Preprocessing
- Converted categorical variables (`director`, `writer`, `genre`) into numerical values:
  - Smoothed means for directors and writers.
  - One-hot encoding for genres.
- Exploded multi-label columns (`director` and `writer`) into a "long format" for accurate processing.
- Split data into training and test sets for evaluation.

### 2. Model Training
- Implemented and evaluated regression models (e.g., Linear Regression).
- Metrics:
  - **R-squared**: Up to 0.88
  - **MSE**: ~69

### 3. Predictions and Export
- Predictions were generated and saved into CSV files for external visualization.
- Exported predictions and actual scores (in separate files) for compatibility with Power BI.

### 4. Visualizations
- Created Power BI dashboards:
  - Scatter plots of actual vs. predicted scores.
  - Bar charts of model performance metrics (e.g., MSE and R-squared).
  - Score distributions within defined brackets (e.g., 0-20, 20-40, etc.).

---

## Results and Insights

- Best model achieved **R-squared: 0.88** and **MSE: 69**.
- Smoothed means for directors and writers were crucial for improving performance.
- Visualization of results in Power BI provided actionable insights.

---

## How to Use

### 1. Preprocessing
Run the provided Python scripts to:
- Process the dataset.
- Convert categorical variables into numerical representations.
- Split the data into training and testing sets.

### 2. Model Training
Train the machine learning model using the script. Predictions and metrics are saved into CSV files.

### 3. Visualization in Power BI
- Import the prediction and actual score files into Power BI.
- Use scatter plots, bar charts, and histograms to analyze the results.

---

## Dependencies

- Python 3.x
- Libraries: Pandas, NumPy, Scikit-learn
- Power BI Desktop

---

## Future Enhancements

- Experiment with advanced algorithms like Gradient Boosting or Neural Networks.
- Add more features to improve prediction accuracy.
- Improve interactive Power BI dashboard.



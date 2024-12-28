# DT Probiotics Data Champion Assignment

## Overview

This repository contains a data analysis and machine learning project focused on predicting company prospects based on various features like revenue, growth rate, and industry.

## Dataset

The dataset used in this project is available in the following [GitHub link](https://github.com/laptopsystem/DT_probiotics_Data_Champion_ASSIGN/blob/main/Task_Records.csv). It contains several company records, with features like:

- **Company_ID**
- **Company_Name**
- **Revenue**
- **Growth_Rate**
- **Industry**
- **Location**
- **Prospect** (Target variable for prediction)

Before using the dataset, ensure you have cleaned and processed it (as done in the project) to remove duplicates and handle missing values.

---

## Project Structure

- **pycharm **: A live web app to interact with the data and models.
- **VS code**: A Jupyter-like notebook to run and modify the code.
- **Dataset**: A CSV file containing company data used for prediction.
- **ML Models**: Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.

---

## Key Features of the Project

1. **Data Cleaning and Preprocessing**: 
   - Handling missing values, removing duplicates, and encoding categorical variables.
   - The "Prospect" column is derived based on the Growth Rate (e.g., companies with growth rate > 20% are classified as 'Yes').

2. **Machine Learning Models**: 
   - Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting are used to predict company prospects.
   - Metrics like **accuracy**, **confusion matrix**, and **classification report** are used to evaluate the models.

3. **Visualizations**:
   - **Scatter plot** showing the relationship between Revenue and Growth Rate.
   - **Correlation matrix heatmap** to understand the relationships between numerical features.
   - **Prospect distribution** by **Industry** and **Location**.
   - **Revenue and Growth Rate** distribution for a better understanding of the data.

4. **Download Processed Data**: 
   - The processed dataset can be downloaded for further analysis.

---

## Requirements

- **Python 3.x** (preferably Python 3.10 or higher)
- **Required Libraries**:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn



---

## Conclusion

This project provides an end-to-end solution for analyzing and predicting company prospects using machine learning. 


# PRODIGY_DS_02

# Titanic Analysis Project

This project aims to explore and analyze the Titanic dataset to gain insights into the demographics of the passengers, their survival rates, and the factors influencing survival. The analysis is conducted using the Python programming language and popular data analysis libraries, including Pandas, NumPy, Seaborn, and Matplotlib.

## Dataset

The Titanic dataset used in this project is sourced from Stanford University's CS109 course archives. The dataset contains information about passengers on the Titanic, including features such as age, gender, passenger class, embarkation point, and survival status.

## Project Structure

- **Data Loading and Initial Exploration:**
  - The dataset is loaded from an online source.
  - Initial exploration involves displaying the first few rows of the dataset and checking for missing values.

- **Data Cleaning:**
  - Missing values in the 'Age' column are filled with the median.
  - Missing values in the 'Embarked' column are filled with the mode.
  - The 'Cabin' column is dropped due to a large number of missing values.
  - A check is performed again to ensure there are no remaining missing values.

- **Exploratory Data Analysis (EDA):**
  - Countplot of survival status.
  - Countplot of survival status with a hue of passenger class.
  - Distribution plot of passenger ages.
  - Countplot of survival status with a hue of gender.
  - Correlation heatmap showing the correlation between different numerical features.

## Visualizations

- Visualizations include countplots to display survival counts, distribution plots for age, and a correlation heatmap.



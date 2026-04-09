# Titanic Dataset Analysis - Task 3

## Overview
This project is an assignment based on the Titanic dataset from Kaggle. It involves:

1. Creating a custom dataset (Part 1)
2. Loading and exploring the Titanic dataset (Part 2)
3. Data cleaning and handling missing values
4. Data analysis using pandas `groupby` and filtering
5. Drawing insights about survival rates

---

## Part 1: Custom Dataset
- Created a dataset with 5 columns:
  - Name, Age, Gender, Score, Passed
- 15 rows with custom index
- Demonstrates how to build a DataFrame from a dictionary

---

## Part 2: Titanic Dataset Analysis

### Steps Taken:

1. **Exploration**
   - `.head()` → display first 5 rows
   - `.info()` → check column types and missing values
   - `.describe()` → statistical summary

2. **Data Cleaning**
   - Fill missing `Age` with median
   - Fill missing `Embarked` with mode
   - Drop `Cabin` column safely (if it exists)
   - Remove duplicates

3. **Data Analysis**
   - Survival rate by gender
   - Survival rate by class
   - Average age per class
   - Survival rate by age group

4. **Filtering**
   - Female passengers who survived
   - Children who survived
   - First class passengers with high survival probability

5. **Insights**
   - Females were more likely to survive
   - Higher class increased survival rate
   - Children had higher survival rates
   - Highest survival: Female + 1st class + young age group

---

## How to Run

1. Open the notebook in **Google Colab**.
2. Upload the dataset `Titanic-Dataset.csv`.
3. Run all cells in order.
4. Outputs include cleaned dataset, analysis results, and filtered views.

---

## Files in this Repository
- `Task3.ipynb` → The Colab notebook with all code and results
- `Titanic-Dataset.csv` → Kaggle Titanic dataset used
- `README.md` → This documentation

---

## Tools Used
- Python 3
- Pandas
- Google Colab

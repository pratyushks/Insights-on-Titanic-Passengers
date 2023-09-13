# Insights-on-Titanic-Passengers
This repository contains Python code and data for conducting an exploratory data analysis (EDA) on the Titanic dataset. The Titanic dataset is a well-known dataset that records information about passengers on the Titanic ship, including whether they survived or not.

## Dataset

The dataset used for this analysis can be found in the following path: `D:\Old\vscodess\Python\EDA\train.csv`.

## Data Preprocessing

- The dataset is loaded into a Pandas DataFrame using the `pd.read_csv()` function.

- Missing values in the 'Age' column are filled with the median age of passengers.

- The 'Cabin' column is dropped as it contains a significant number of missing values.

- Missing values in the 'Embarked' column are filled with the mode (most frequent value) of the column.

## Analysis

1. **Survival Rate by Passenger Class**

2. **Number of Survivors by Passenger Class**

3. **Survival Rate by Gender**

4. **Number of Survivors by Gender**

5. **Survival Rate by Age Group**

6. **Number of Survivors by Age Group**

7. **Survival Rate by Size of Family**

8. **Number of Survivors by Size of Family**

9. **Survival Rate by Embarkation Port**

10. **Number of Survivors by Embarkation Port**

11. **Number of Survivors by Age Group and Survival Status**

## Dependencies

- Python 3
- Pandas
- Matplotlib
- Seaborn

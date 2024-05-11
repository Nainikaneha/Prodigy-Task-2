# PRODIGY_DS_02
Perform data Cleaning and (EDA) on a dataset, Titanic_Dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.
# Titanic Dataset Analysis
This project involves exploring the Titanic dataset using Python and various data analysis libraries, such as pandas, numpy, matplotlib, and seaborn. The Titanic dataset contains information about passengers on board the Titanic and whether they survived or not.

## Getting Started
To get started, make sure you have the necessary Python libraries installed. You can install them using pip:
pip install pandas numpy matplotlib seaborn

git clone <repository_url>
cd <repository_directory>
Make sure you have the Titanic dataset file (Titanic_Dataset.csv) in the same directory.

# Data Cleaning
In the data cleaning phase, we performed the following operations:

- Handling missing values:
- Age: Missing values were replaced with the median age.
- Embarked: Missing values were replaced with the mode (most common value).
  
# Exploratory Data Analysis (EDA)
## Summary Statistics
We displayed the summary statistics of the dataset using df.describe().

## Data Overview
We displayed the first few rows of the dataset to get an overview of its structure using df.head().

## Data Information
We printed information about the dataset, including data types and non-null counts using print(df.info()).

## Data Visualization
We used data visualization techniques to explore relationships and patterns in the dataset:

- Survival by Sex: We created a count plot to visualize survival by gender.
- Survival by Passenger Class: We created a count plot to visualize survival by passenger class.
- Survival by Age: We used a histogram to visualize the age distribution of survivors and non-survivors.
- Survival by Fare: We used a histogram to visualize the fare distribution of survivors and non-survivors.
- Correlation Heatmap: We generated a heatmap to visualize the correlation between various numerical features and survival.

## Age and Fare Distribution
We explored the distribution of passengers' ages and fares using histograms.

# Data Preprocessing
One-hot Encoding: We performed one-hot encoding on the 'Embarked' column to convert categorical data into numerical format.

# Conclusion
This analysis provides valuable insights into the Titanic dataset, including the distribution of passengers, relationships between variables, and patterns related to survival. Notable findings include the higher survival rate among females, first-class passengers, children, and passengers who paid higher fares.

These insights can serve as a foundation for further analysis or machine learning models aimed at predicting passenger survival. Feel free to explore and expand upon this analysis to gain deeper insights into the data.


Feel free to modify and expand upon this analysis as needed.

# US-University-Recommendation


Applying to universities in the United States can be overwhelming due to the sheer number of institutions and the complexity of evaluating each one based on individual preferences. This project aims to simplify the process by building a University Recommendation Model, leveraging a comprehensive dataset of US colleges and universities.

## Features

Data Cleaning: Identified and handled missing values effectively to ensure data quality.

Categorical Encoding: Applied one-hot encoding for categorical variables like institution type and operational status.

Exploratory Data Analysis (EDA): Analyzed patterns, correlations, and trends in key attributes such as population, enrollment, and geographic distribution.

Visualization: Generated histograms to identify well-behaved features and potential transformations needed for model accuracy.

## Dataset Description

The dataset includes extensive information about universities:

Geolocation: Latitude, longitude, and city/state details.

Demographics: Total enrollment, part-time vs. full-time students, housing capacity.

Operational Details: Institution type, sector, and operational status.

## Key Columns

POPULATION: Total student population.

TOT_ENROLL: Total enrollment across full-time and part-time categories.

INST_SIZE: Institution size classification.

STATUS: Operational status (active, closed, merged, etc.).

DORM_CAP: Dormitory capacity.

## Data Preprocessing

Handling Missing Values: Addressed null records by dropping rows or replacing placeholder values (-999, -3) with NaN.

Encoding: Converted categorical columns such as STATUS, TYPE, and LEVEL_ into dummy variables for compatibility with machine learning algorithms.

Outlier Detection: Identified and visualized extreme values in key numerical columns like POPULATION and TOT_ENROLL for further analysis.

## Exploratory Data Analysis

Univariate Analysis: Histograms of numerical features like population and enrollment helped identify data distribution and skewness.

Insights:

Significant variability in student population across institutions.

Negative placeholders in columns like INST_SIZE and LOCALE indicate data inconsistencies.

Geographic coordinates are consistent with US institutions but require further validation for extreme values.

## Future Enhancements

Develop a personalized AI-powered recommendation engine to match students with universities based on preferences like location, size, and courses offered.

Incorporate advanced data imputation techniques to handle missing or inconsistent values.

Utilize clustering algorithms to group similar institutions and refine recommendations.

## How to Use

Dataset Preparation: Load the cleaned dataset into the model.

EDA Scripts: Use provided scripts for visualization and preprocessing.

Recommendation Engine: Apply the trained model to generate university recommendations.

## Technologies Used

Python: For data analysis and preprocessing.

Pandas: Handling and cleaning data.

Matplotlib/Seaborn: Data visualization.

NumPy: Numerical operations.

## Conclusion

This project bridges the gap between students and their ideal universities, combining data science with education to create meaningful impact. The groundwork laid here can evolve into a sophisticated, user-centric recommendation system.

## Contact

Feel free to reach out for collaboration or feedback! 😊

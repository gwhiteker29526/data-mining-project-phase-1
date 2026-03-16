# data-mining-project-phase-

## Dataset Summary
This project uses the Diabetes Health Indicators BRFSS 2015 dataset. The dataset contains over 250,000 survey responses and more than 20 attributes related to health conditions, lifestyle, and demographics. It is well-suited for data mining tasks such as classification, regression, clustering, and association rule mining.

## Why This Dataset
I selected this dataset because it exceeds the minimum project requirements and provides a strong mix of categorical, binary, ordinal, and numeric attributes. It also addresses a practical real-world problem: identifying factors associated with diabetes risk.

## Major Steps Performed
- Loaded the dataset using Pandas
- Inspected structure, data types, and summary statistics
- Checked for missing values and duplicates
- Removed duplicate records where needed
- Validated feature values for consistency
- Performed exploratory data analysis using Matplotlib and Seaborn
- Examined class distribution, feature distributions, outliers, and feature relationships

## Key Insights
- The target variable appears imbalanced, which will affect later classification modeling
- BMI, age, and health-condition variables appear to be strongly related to diabetes outcomes
- Several numeric variables may need scaling for future clustering or regression tasks
- The dataset is rich enough to support later feature engineering and data mining steps

## Challenges Encountered
- Some variables are encoded numerically and require careful interpretation
- Large dataset size can make some plots slow, so sampling may be used for visualization
- Outliers in variables like BMI and health-day counts require review before modeling

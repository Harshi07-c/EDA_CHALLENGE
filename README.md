# EDA_CHALLENGE

This Python script utilizes various data analysis and visualization techniques to explore and understand the World Data for the year 2023. The dataset contains information about different countries, covering a wide range of indicators, including demographic, economic, and geographical aspects.

1) Data Loading and Preprocessing:
The script begins by loading the World Data 2023 dataset using Pandas.
Columns with irrelevant information are dropped.
Numeric columns are identified for further analysis.

2) Handling Missing Values:
KNN imputation is applied to handle missing values in numeric columns.

3) Exploratory Data Analysis (EDA):
Descriptive statistics and visualizations, such as histograms and box plots, are used to understand the distribution of numeric features and identify outliers.
A correlation matrix and heatmap are generated to visualize relationships between numeric features.
Scatter plots reveal correlations between highly correlated variable pairs.
Factors influencing GDP are identified through correlation analysis, providing insights into which features may contribute to GDP growth.

4) Categorical Variables Analysis:
The distribution of a categorical variable ("Official language") is visualized using a horizontal bar plot.

5) Geographic Visualization:
GeoPandas is employed to create a choropleth map depicting the distribution of official languages across different countries.

Conclusion and Recommendations:
The script concludes with a brief summary of insights, including the identification of factors that may influence GDP. Recommendations are provided for potential strategies to increase GDP based on the correlation analysis.

I participated in an EDA challenge organized by Women Who Code Data Science. The link to this dataset : https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023

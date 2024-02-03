# EDA_CHALLENGE

This Python script utilizes various data analysis and visualization techniques to explore and understand the World Data for the year 2023. The dataset contains information about different countries, covering a wide range of indicators, including demographic, economic, and geographical aspects.

1) Data Loading and Preprocessing:  
1)The script begins by loading the World Data 2023 dataset using Pandas.
2)Columns with irrelevant information are dropped.
3)Numeric columns are identified for further analysis.

3) Handling Missing Values:
   KNN imputation is applied to handle missing values in numeric columns.

4) Exploratory Data Analysis (EDA):  
1)Descriptive statistics and visualizations, such as histograms and box plots, are used to understand the distribution of numeric features and identify outliers.
2)A correlation matrix and heatmap are generated to visualize relationships between numeric features.
3)Scatter plots reveal correlations between highly correlated variable pairs.
4)Factors influencing GDP are identified through correlation analysis, providing insights into which features may contribute to GDP growth.

5) Categorical Variables Analysis:
   The distribution of a categorical variable ("Official language") is visualized using a horizontal bar plot.

6) Geographic Visualization:
   GeoPandas is employed to create a choropleth map depicting the distribution of official languages across different countries.

Conclusion and Recommendations:
The script concludes with a brief summary of insights, including the identification of factors that may influence GDP. Recommendations are provided for potential strategies to increase GDP based on the correlation analysis.

I participated in an EDA challenge organized by Women Who Code Data Science. The link to this dataset : https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023

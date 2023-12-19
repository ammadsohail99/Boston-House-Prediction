# Overview
In a data-driven world, accurate prediction based on historical and current data is invaluable, especially in the real estate sector. This project focuses on the Boston housing market, employing statistical models to predict house prices. The aim is to navigate the complexities of real estate data and extract meaningful insights.

# Data Description
The dataset includes 506 properties in the Boston area, with variables covering various aspects inlcuding:

- CRIM: Per capita crime rate by town
- ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: Proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: Nitric Oxide concentration (parts per 10 million)
- RM: The average number of rooms per dwelling
- AGE: Proportion of owner-occupied units built before 1940
- DIS: Weighted distances to five Boston employment centers
- RAD: Index of accessibility to radial highways
- TAX: Full-value property-tax rate per 10,000 dollars
- PTRATIO: Pupil-teacher ratio by town
- LSTAT: % lower status of the population
- MEDV: Median value of owner-occupied homes in 1000 dollars (target variable)

To run this project, you will need **Python** and several libraries, including **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, **Statsmodels** and **Scikit-Learn**. You can install these libraries using pip

# Exploratory Data Analysis
This involved running univariate and bivariate analysis on the dataset.

# Data Preprocessing
Preprocessing involved handling missing values, feature engineering, data transformation, and outlier analysis. This ensured a robust foundation for the models.

# Model Selection and Refinement
The process included initial dataset refinement (mean of residuals to be zero, no heteroskedasticity, linearity of variables and normlaity of error terms), development of regression models, and model comparison. Techniques like stepwise regression and evaluation metrics like R-squared and MSE were used.

# Results
The model achieved an R-squared value of 0.729 (+/- 0.232) , explaining 72.9% of the variance in house prices. The MSE was 0.041 (+/- 0.023), indicating the model's accuracy.

# Conclusion
The project offers insights into the Boston housing market and serves as a tool for stakeholders in making informed decisions. Therefore, for the house price to increase, the presence of the bounding river seems to be a key player. A person looking forward to inquiring about the price must ensure what is the locality and inquire about the presence of a bounding river. Similarly, a town or suburb must monitor its nitric oxide concentration as it seems to be playing a crucial part in determining house prices. As we all know that the presence of all types of vehicles around us has increased significantly, which means that the nitric oxide emissions must have increased too, therefore, the house prices must have been affected by that as well. People looking to buy a house in any town or suburb must consider the vehicle inflow and outflow in that particular town or suburb.

# Acknowledgments
This project was completed as a part of the MIT - Applied Data Science Program. Special thanks to MIT Professional Education for providing the dataset and the opportunity to work on this insightful analysis. Their support and resources were invaluable in the successful completion of this project.

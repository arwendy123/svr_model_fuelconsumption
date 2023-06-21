In this analysis, an exploratory data analysis (EDA) was conducted on the "FuelConsumptionCo.csv" dataset. The dataset was loaded and a thorough overview of the data was obtained, including information about the columns, the first few rows, and summary statistics. Visualizations were created to gain insights into the data, such as the distribution of the target variable "CO2EMISSIONS" and the distributions of numerical features like "ENGINESIZE," "CYLINDERS," and various fuel consumption measures.

Furthermore, the relationships between numerical features were examined through a correlation matrix and heatmap visualization. Additionally, scatter plots were used to explore the relationships between highly correlated features ("ENGINESIZE" and "FUELCONSUMPTION_COMB") and the target variable. Categorical features such as "MAKE," "MODEL," "VEHICLECLASS," and "TRANSMISSION" were analyzed using count plots and box plots to understand their distributions and relationships with the target variable.

To develop a predictive model, a Support Vector Regression (SVR) model was implemented. The dataset was split into training and testing sets, and the SVR model was created and trained using the training data. Predictions were made on the test set, and the model's performance was evaluated using mean squared error (MSE) and R2 score as metrics.

Overall, this analysis encompassed a comprehensive exploration of the dataset, including data visualization, correlation analysis, and the development of an SVR model for predicting CO2 emissions based on vehicle characteristics.

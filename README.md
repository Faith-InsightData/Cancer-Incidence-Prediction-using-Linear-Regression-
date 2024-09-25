# Cancer-Incidence-Prediction-using-Linear-Regression-
Project Overview This project aims to develop a linear regression model to predict the Age-Adjusted Incidence Rate of cancer using related variables such as confidence intervals and average annual counts. The insights gained from this model could guide resource allocation, enhance public health initiatives, and fuel further research in oncology

# Cancer Incidence Prediction using Linear Regression ♋️📊
Project Overview
This project aims to develop a linear regression model to predict the Age-Adjusted Incidence Rate of cancer using related variables such as confidence intervals and average annual counts. The insights gained from this model could guide resource allocation, enhance public health initiatives, and fuel further research in oncology.

# 🎯 Project Goal
The primary objective is to create a model that accurately predicts cancer incidence rates based on the available data. This information can significantly impact health policy decisions and research funding priorities.

# 🚀 Getting Started
To get started with this project, follow the steps below:

Prerequisites:

Ensure you have Python installed (preferably version 3.7 or higher).
Install necessary libraries if you haven't already. You can use pip to install the required packages:

pip install pandas numpy scikit-learn matplotlib seaborn
Data:

This project utilizes two CSV files: incd.csv and cancer_data_notes.csv. Ensure these files are located in the same directory as your Jupyter notebook or Python script.

## 🗂️ Dataset
The dataset used in this project is sourced from the incd.csv file. It contains the following key information regarding cancer incidence rates:

Age-Adjusted Incidence Rate (cases per 100,000)
Lower and Upper 95% Confidence Intervals
Average Annual Count
## 🛠️ Methodology
## 🛠️ Methodology

# 1. Data Cleaning 🧹
Non-numeric Characters Removal: Remove any non-numeric characters from relevant columns to prepare the data for modeling.
Handling Missing Values: Missing values are addressed, typically by dropping rows with insufficient data to maintain the integrity of the dataset.

# 2. Exploratory Data Analysis (EDA) 🔍
Descriptive Statistics: Calculate essential statistics (mean, standard deviation, etc.) for the target variable and features to understand data characteristics.
Data Visualization: Use histograms and scatter plots to visualize distributions and relationships between variables.
Correlation Matrix: Generate a correlation matrix to explore relationships and identify potential predictors for the model.

# 3. Model Building 🏗️
Data Splitting: Divide the dataset into training and testing sets, typically with a 70/30 split, to evaluate model performance.
Model Initialization: Create and train a linear regression model using the training data.
# 4. Model Evaluation 📈
*Performance Metrics: Assess model performance using R² and RMSE metrics to quantify how well the model predicts the target variable.
*Residual Analysis: Conduct residual analysis to validate model assumptions regarding normality and homoscedasticity.
* Multicollinearity Check: Utilize the Variance Inflation Factor (VIF) to check for multicollinearity among predictor variables.
# 📊 Results

*The model achieved an R² score of r2, indicating the proportion of variance explained by the model.
*The RMSE value was found to be rmse, representing the average magnitude of prediction error.
*Coefficients for each predictor variable were obtained, indicating their relative impact on the Age-Adjusted Incidence Rate.

# 📉 Limitations
*The model may exhibit limitations due to potential non-linear relationships not captured by linear regression.
*Prediction accuracy may be constrained by the quality and availability of the data.

📈 Future Work
*Explore alternative regression models (e.g., polynomial regression) that may offer improved performance.
*Include additional relevant features to enhance prediction accuracy.
*Apply regularization techniques (like Lasso or Ridge regression) to mitigate overfitting.
*Conduct further analyses to interpret results and identify potential causal relationships.

# 🤝 Contributions
Contributions to this project are welcome! Feel free to submit pull requests for enhancements or bug fixes.

# 🌟 Acknowledgements
This project utilized publicly available cancer incidence data.
Special thanks to the open-source community for developing essential libraries such as pandas, scikit-learn, and matplotlib. 
# 📜 License
This project is licensed under the MIT License.

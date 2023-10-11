# Diabetes_Dataset_Linear_Regression

### Dataset

The dataset used for this analysis is the Diabetes dataset from scikit-learn. 
It contains ten baseline variables (age, sex, BMI, average blood pressure, and six blood serum measurements) and a quantitative measure of disease progression one year after baseline.

### Steps
The analysis includes the following steps:

1. Data Exploration and Visualization:

  + Evaluated basic dataset statistics.
  + Visualized relationships through Correlation matrix heatmap and Pairplot for selected features.
  + Mapped the distribution of the target variable.
    
2. Splitting Data:
+ Split the dataset into training and testing sets in a 80:20 ratio.

3. Linear Regression Model:

+ Fit a Linear Regression model to the training dataset.
4. Model Evaluation:

+ Calculated Root Mean Squared Error (RMSE) and R-squared (R2) for model evaluation.
+ We also performed K-Fold Cross-Validation and calculated RMSE and R2.
5. Residual Analysis:

+ Visualized residuals against the predicted values.
+ Checked the normality of residuals with histograms and QQ plots.
6. Regression Plot:

+ Created a regression plot for a selected feature using Seaborn.

 ### Conclusion
+ In this project, we performed a regression analysis on the diabetes dataset.
+ The analysis in conjunction with visualizations provide insights into the relationships between various features (medical metrics) and diabetes progression.
+ We built a linear regression model, analysed it, and performed residual analysis.

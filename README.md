<h2>About the Data</h2>
The dataset chosen for this analysis contains Black Friday sales predictions. It includes numerical features like product categories, purchase values and categorical features like occupation, marital status, gender and age. The target variable is "Purchase".
<br>
<br>
<h2>Exploratory Data Analysis and Preprocessing</h2>
During data exploration and preprocessing steps, I examined the distribution of each feature, checked for missing values, and looked for potential outliers. Data cleaning involved handling missing values, removing outliers if necessary, and encoding categorical variables if applicable. Feature engineering in the later step of training included creating polynomial features to capture non-linear relationships between predictors and the target variable.
<br>
<br>
<h2>Objectives</h2>
The main objective of this analysis is to develop linear regression models to predict the target variable accurately while maintaining interpretability. The focus is primarily on prediction, but it's essential to understand the relationships between the predictors and the target variable for interpretability purposes.
<br>
<br>
<h2>Summary of Linear Regression Models:</h2>
<br>
Four linear regression models were trained and evaluated:
<br>
<br>
Simple Linear Regression Model: This model served as the baseline and used the original features without any modifications.
<br>
<br>
Linear Regression Model with Polynomial Features Applied: Polynomial features up to the second degree were added to the original features to capture non-linear relationships.
<br>
<br>
Regularization Regression Models (Ridge and Lasso Regression): Ridge and Lasso regressions was applied to mitigate multicollinearity and overfitting by introducing regularization.
<br>
<br>
<b>Recommendation for Final Model:</b>
<br>
<br>
Based on the results, the polynomial regression model appears to be the most suitable final model. It achieved the lowest root mean squared error (RMSE) and a relatively higher coefficient of determination (R^2 score) compared to the other models. Moreover, the polynomial regression model captures non-linear relationships between predictors and the target variable, enhancing its predictive performance. Additionally, its coefficients can provide insights into the importance of different features in predicting the target variable.
<br>
<br>
<h2>Insights and key findings</h2>
The polynomial regression model outperforms the other models in terms of predictive accuracy.
<br>
<br>
Adding polynomial features improves the model's ability to capture complex relationships between predictors and the target variable.
<br>
<br>
Regularization techniques like Ridge and Lasso regression did not significantly improve the model's performance in this case.

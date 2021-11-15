# Black-Friday-Sales-Prediction
### Abstract – 
Black Friday marks the beginning of the Christmas shopping festival across the US. On Black Friday big shopping giants like Amazon, Flipkart, etc. lure customers by offering discounts and deals on different product categories. The product categories range from electronic items, Clothing, kitchen appliances, DÃ©cor. Research has been carried out to predict sales by various researchers. The analysis of this data serves as a basis to provide discounts on various product items. With the purpose of analyzing and predicting the sales, we have used three models. The dataset Black Friday Sales Dataset available on Kaggle has been used for analysis and prediction purposes. The models used for prediction are linear regression, lasso regression, ridge regression, Decision Tree Regressor, and Random Forest Regressor. Mean Squared Error (MSE) is used as a performance evaluation measure. Random Forest Regressor outperforms the other models with the least MSE score.

### Data Pre-processing
Data preprocessing which mainly includes filling missing values is performed. The categorical values are label encoded to numeric form. The categories such as Gender where F represents female and M represents Male is converted to numerical form as 0 and 1 also other categorical values such as City_Category, Stay_In-Current_City, Age are converted to numerical form by applying Label Encoding.

### DATASET VISUALIZATION
Heatmap is used for determining the correlation between dataset attributes. The data of a given dataset can be easily represented graphically by using a Heatmap. It uses a color system to represent the correlation among different attributes. It is a data visualization library (Seaborn) element.
![image](https://user-images.githubusercontent.com/89696170/138823925-b8540533-87dd-4f0c-be51-7cd121a5cbe7.png)

Heatmap color encoded matrix can be described as lower the intensity of the color of an attribute related to the target variable, higher is the dependency of target and attribute variables.

### RESULTS & DISCUSSION
#### 1.Linear Regression
Linear Regression is one of the supervised machine learning algorithms . A regression problem can be stated as a case when the output variable is continuous . Linear regression predicts a dependent variable (y) based on a given independent variable (x). The model depicts a linear relation among the variables.

#### 2.Lasso Regression and Ridge Regression
Lasso Regression provides both variable selection and regularization . It makes use of soft thresholding. Only a subset of the covariates provided is select for use in the final model in the case of Lasso regression
Multiple regression data can be analyzed using Ridge Regression . Least Square estimates are unbiased when multicollinearity occurs. Based on the degree of bias it reduces the standard errors that is added to the regression estimates.

#### 3.Decision Tree Regressor
The Decision Tree model builds a tree-like structure for regression or classification models . The dataset is simply broken down into smaller subsets. In a DT the control statements or values are a basis for branching, and the splitting node contains data points on either side, depending on the value of a specific attribute. The attribute selection measure plays an important role in root node selection.

#### 4.RandomForest Regressor
Random Forest being an ensemble technique is capable of both tasks namely regression and classification. The Random Forest is based on the ideology of combining multiple DT rather than single DT dependency.

### Comparitive Analysis
Model                              Mse
Linear Regression
Lasso and Ridge Regression
DecisionTree Regressor
RandomForest Regressor

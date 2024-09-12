# Customer_churn_prediction_machine_learning
# I. Introduction
## 1. About the project
- This project focuses on building a machine learning model to predict customer churn for an e-commerce company. Customer churn is a significant issue that directly affects the revenue and growth of a business. By accurately predicting customers who are at high risk of churning, businesses can proactively implement customer retention strategies. The goal of the project is to build a reliable predictive model that provides insights to reduce churn rates and improve customer loyalty.
## 2. Business Question
- What are the behaviors/characteristics of customers who churn? Propose solutions to retain customers
- Build a Machine Learning model to predict customer churn
- Based on the behavior of churning customers to group churning customers and analyze the differences between the groups to have upcoming special gift programs
## 3. Dataset
- Dataset is a collection of customer information of an e-commerce company that has been labeled as churning or not churning
## 4. Data Description
Dataset bao gồm 20 trường:
- CustomerID: Customer identifier
- Churn: label with 1 for churn and 0 for not churn
- Tenure: The number of weeks from the date the account was registered to the date of data extraction
- PreferredLoginDevice: Preferred login device of customer
- CityTier: Customer City Cluster
- WarehouseToHome: Distance in between warehouse to home of customer
- PreferredPaymentMode: Customer Payment Method
- Gender: Gender of customer
- HourSpendOnApp: Number of hours spend on mobile application or website
- NumberOfDeviceRegistered: Total number of deceives is registered
- PreferedOrderCat: Categories that customers often buy last month
- SatisfactionScore: Satisfactory score of customer on service
- MaritalStatus: Marital status of customer
- NumberOfAddress: Total number of added added on particular customer
- Complain: Any complaint has been raised in last month
- OrderAmountHikeFromlastYear: Percentage increases in order from last year
- CouponUsed: Total number of coupon has been used in last month
- OrderCount: Total number of orders has been places in last month
- DaySinceLastOrder: Day Since last order by customer
- CashbackAmount: Average cashback in last month
# II. Techniques used
- **Python Programming Language:**
Python serves as the primary programming language for data analysis, modeling, and implementation of machine learning algorithms due to its rich ecosystem of libraries and packages
- **Pandas**: 
Pandas is used for data manipulation and analysis. It provides data structures and functions for effectively working with structured data, such as CSV files or databases.
- **NumPy**:
NumPy is a fundamental package for numerical computing in Python. It provides support for large, multi-dimensional arrays and matrices, along with a wide range of mathematical functions to operate on these arrays.
- **Matplotlib and Seaborn**:
Matplotlib is used for creating static, interactive, and animated visualizations in Python. Seaborn is built on top of Matplotlib and provides a high-level interface for creating informative and attractive statistical graphics
- **Scikit-Learn (sklearn)**:
Scikit-Learn is a machine learning library in Python that provides a wide range of tools for various machine learning tasks such as classification, regression, clustering, model selection, and more
- **Random Forest Classifier**:
Random Forest is an ensemble learning algorithm that combines multiple decision trees to create a more robust and accurate model. It's used for both classification and regression tasks
- **Model Evaluation Metrics**:
Various metrics like accuracy, precision, recall, F1-score, confusion matrix, ROC curve, and AUC (Area Under Curve) are used to assess the performance of the machine learning models
- **K-Nearest Neighbors (KNN)**:
The KNN algorithm can be considered a voting system, where the majority class label determines the class label of a new data point among its nearest ‘k’ (where k is an integer) neighbors in the feature space
- **StandardScaler**:
StandardScaler is used for standardizing features by removing the mean and scaling to unit variance. It's an important preprocessing step in machine learning to ensure features are on similar scales.
- **Principal Component Analysis (PCA)**:
PCA is a dimensionality reduction technique that transforms the data into a new coordinate system while preserving as much variance as possible. It's useful for reducing the complexity of high-dimensional data
- **GridSearchCV**:
GridSearchCV is used for hyperparameter tuning, where a set of hyperparameters are tested exhaustively to find the combination that produces the best performance for the model
- **Cross-Validation**:
Cross-validation is a technique used to evaluate the generalization performance of a model by splitting the dataset into multiple subsets (folds) for training and testing
- **Standard Machine Learning Libraries**:
The project utilizes standard machine learning libraries like SciPy and scikit-learn for various tasks including preprocessing, model selection, hyperparameter tuning, and model evaluation.
# III. Implementation steps
- **Step 1**: Exploratory Data Analyst - EDA
- **Step 2**: Analyze customer churn behavior
- **Step 3**: Build the Machine Learning model for predicting churned users
- **Step 4**: Model Evaluation
- **Step 5**: Segmentation of churning customers    
# IV. Outcome
- Analyze churn behavior mostly from new customers or old customers with complaints and make recommendations to retain new customers and take care of old customers
- Build and refine a customer churn prediction model with Accuracy 97%, Precision 94%, Recall 86%, F1-Score 90%
- Segment churning customers into 7 groups and show the differences between the groups

SUMMARY OF THE PROJECT

FicZon Inc, an IT solution provider, relies heavily on digital channels for leads, particularly through their website. With a significant dependence on sales force effectiveness, FicZon has experienced a decline in sales due to market maturation and increased competition.

The current lead quality assessment relies on manual categorization by the sales staff, with a post-analysis focus. Recognizing the need for improvement, FicZon initiated a project with the goal of leveraging Machine Learning (ML) to pre-categorize leads, anticipating a substantial boost in sales effectiveness.

The project's primary objectives included data exploration insights into sales effectiveness and the development of an ML model capable of predicting lead categories (High Potential or Low Potential). Various machine learning models were employed to achieve these goals. 

The implementation of ML aimed to enhance the accuracy and efficiency of lead categorization, ensuring a proactive approach to sales, and addressing the challenges posed by market dynamics and emerging competitors.

The dataset for the Business case was obtained through SQL server using MySQL Workbench. It has 7422 rows × 9 columns with column names as 'Created', 'Product_ID', 'Source', 'Mobile', 'EMAIL', 'Sales_Agent', 'Location', 'Delivery_Mode' and 'Status'. The dataset contains all these details for 7422 products which were sold to different customers. 

It is a Supervised Learning Classification problem with input features as Categorical Data and target as the 'Status' where different values are recorded providing whether that particular Product is at what stage (Open, lost, Just Enquiry etc). The predictor variables as well as the target variable 'Status' is nominal type.

Machine Learning algorithms used:

1. Logistic Regression
2. Support Vector Machine
3. Naive-Bayes
4. Decision Tree
5. XGBoost
6. Random Forest
7. K-nearest Neighbours
8. K-Means

Methodology:
Most of the columns have a lot of different unique labels. Hence, these labels were merged and new labels were formed categorizing the labels with similar features into one group. After categorizing, the categorical data were converted to Numerical type using Label Encoding Technique.

The Target variable 'Status' was categorized into 'Good' and 'Bad' which referred to High Potential and Low Potential Lead respectively.

SMOTE is used for balancing the sample data. After various Data Preprocessing and Feature Engineering Process, different Machine Learning Algorithms like Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, XGBoost, K-Means, K-NN and Naive-Bayes algorithms were used for prediction.

CONCLUSION

The Main purpose of the project was to find out the Lead Quality which can significantly increase the sales.

After trying various Machine Learning Model on the given data set, based on the Accuracy score, Recall score, Precision score and F1 score, it can be concluded that out of all the algorithms, **Support Vector Machine** is performing best with highest accuracy score.
**It can concluded that SUPPORT VECTOR MACHINE (SVM) algorithm is the best performing model on this Data set.**

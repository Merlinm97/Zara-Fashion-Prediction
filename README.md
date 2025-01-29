Zara Clothing Collection Dataset and Prediction Model

This project involves the analysis and prediction of Zara's clothing collection dataset, which includes fashion items categorized by type (e.g., shirts, pants, trousers) and gender (Men/Women). The dataset consists of product names, descriptions, images, prices, and genders.

Key Features:

The dataset is analyzed to predict the gender of products (Men/Women) based on various classifiers such as Decision Trees, Random Forest, Gradient Boosting, and XGBoost.
Data preprocessing techniques like SMOTE are applied to handle class imbalance.
Several models are trained and evaluated, with the best-performing model achieving an accuracy of 85.39% using a Decision Tree Classifier.
Streamlit Web Application: A user-friendly web app built using Streamlit allows users to filter products based on gender, dress type, and price range. The filtered dataset is displayed with product images, prices, and details. The app also integrates the trained model for predictions.

Model Evaluation:

Best classifier: DecisionTreeClassifier with a maximum depth of 30
Accuracy: 85.39%
Hyperparameter tuning using RandomizedSearchCV and GridSearchCV to achieve optimal model performance.

# ML-DecisionTreeRegressor
Diabetes Prediction using Decision Tree Regressor

This project focuses on predicting disease progression using the Diabetes dataset and a Decision Tree Regressor. The dataset was loaded using Scikit-learn and converted into a DataFrame for easier analysis and preprocessing.

The features and target variable were separated, and the dataset was split into training and testing sets using train_test_split. A DecisionTreeRegressor model was trained with optimized hyperparameters such as max_depth=9 and min_samples_leaf=30 to control overfitting and improve generalization.

Model performance was evaluated using Mean Absolute Error (MAE) and R² Score on both training and testing datasets.

📈 Model Performance
MAE (Train): 44.44
MAE (Test): 43.72
R² Score (Train): 0.48
R² Score (Test): 0.43
🔍 Key Highlights
Implemented Decision Tree Regression for continuous value prediction
Controlled overfitting using hyperparameters
Evaluated model using MAE and R² metrics
Visualized the decision tree using plot_tree for better interpretability

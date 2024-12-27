# CSE445-Machine-Learning-Project-on-EPL-data-analysis-and-prediction
Transfers of players in professional football involve high financial investments, so objective estimation using
a data-driven approach requires the support of machine learning techniques to predict the transfer values
of the Premier League players based on a dataset of performance metrics, demographic attributes, and
financial records. The methodology embraces broad preprocessing steps, including log transformations, onehot encoding of categorical features, and standardization of numerical features, followed by a stratified traintest split to maintain class balance. Several regression algorithms were explored, such as Linear Regression,
Decision Trees, Random Forest, Support Vector Regression, and k-Nearest Neighbors, both in their baseline
form and after tuning their hyperparameters. Results point out Random Forest and its tuned version as the most reliable models, balancing
predictive accuracy and interpretability. SHAP, a technique of explaining machine learning models, was used
to uncover feature importance, and it is clear that player market value, contract length, and performance
indicators make a significant difference in the prediction

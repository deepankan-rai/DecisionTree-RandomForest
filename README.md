# DecisionTree-RandomForest

1. Data Preprocessing
  Loaded dataset using pandas.read_csv().
  Identified and separated features (X) and target (y).
  Handled categorical variables with one-hot encoding.
  Imputed missing values using the median strategy.
  Standardized numeric features with StandardScaler.
2. Decision Tree Classifier
  Trained a basic Decision Tree.
  Visualized the structure of the tree (first 3 levels for clarity).
  Checked accuracy and classification metrics.
3. Overfitting Analysis
  Trained multiple trees with varying max_depth.
  Plotted train vs test accuracy to observe overfitting.
  Used GridSearchCV to find the best hyperparameters.
4. Random Forest Classifier
  Trained a Random Forest (ensemble of multiple trees).
  Compared test accuracy with Decision Tree results.
5. Feature Importances
  Extracted and visualized the most important features for both models.
6. Cross-Validation
  Performed 5-fold Stratified Cross-Validation.
  Reported average accuracy and stability of both models.

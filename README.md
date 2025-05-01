This project focuses on building and evaluating classification models using the Heart Disease dataset.
It demonstrates how to train a Decision Tree and a Random Forest, analyze overfitting, interpret feature importances, and perform model evaluation using cross-validation.
🔍 Project Tasks

✅ 1. Train a Decision Tree Classifier and Visualize the Tree
Used sklearn.tree.DecisionTreeClassifier
Trained the model on standardized features
Visualized the tree using plot_tree()

✅ 2. Analyze Overfitting and Control Tree Depth
Plotted train/test accuracy vs max_depth
Identified overfitting at higher depths
Selected optimal depth for best generalization

✅ 3. Train a Random Forest and Compare Accuracy
Used sklearn.ensemble.RandomForestClassifier
Achieved higher and more stable accuracy compared to the decision tree

✅ 4. Interpret Feature Importances
Extracted feature importances from the Random Forest
Visualized the most influential features using a horizontal bar chart

✅ 5. Evaluate Using Cross-Validation
Performed 5-fold cross-validation using cross_val_score()
Compared average cross-validation accuracy for Decision Tree and Random Forest

📊 Key Libraries
pandas, numpy
matplotlib, seaborn
sklearn.model_selection
sklearn.tree, sklearn.ensemble
sklearn.metrics

# Diabetes_prediction_with_KNN
This project implements an optimized machine learning pipeline for predicting diabetes by combining dimensionality reduction, wrapper-based feature selection, and distance-based classification. Instead of relying on a plain model, the focus is on improving generalization, reducing noise, and selecting only the most informative features.

# 🔥 Why this project?

Most ML notebooks stop at “train → accuracy → done.”
This project goes deeper.

It builds a noise-free, optimized, Kaggle-ready classification engine that carefully selects only the most meaningful information before making medical predictions.

Less noise. More signal. Smarter predictions.

# 🧠 What’s happening under the hood?

Raw Medical Data
      ↓
Feature Scaling
      ↓
Principal Component Analysis (PCA)
      ↓
Sequential Feature Selection (mlxtend)
      ↓
Distance-Weighted KNN Classifier
      ↓
Probability-Based Predictions

# ✂️ Smart Feature Pruning

• 24 original features
• Reduced to 22 PCA components
• Further refined to only 9 elite components using Sequential Feature Selection

(0, 3, 4, 6, 10, 12, 18, 19, 21)

# Fewer features → Faster model → Better generalization.

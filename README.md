# iris-expert-dashboard
Iris Expert ML Dashboard – An interactive Streamlit app for training, comparing, and testing machine learning models on the Iris dataset. Includes feature engineering, multi-sample predictions, accuracy comparison, confusion matrices, and interactive visualizations.
# 🌸 Iris Expert ML Dashboard

An **interactive Streamlit app** for the Iris dataset, designed for machine learning enthusiasts, students, and data scientists.

## Features

- **Load & Explore Dataset**: Upload your own Iris CSV file and preview the data.
- **Feature Engineering**: Automatic calculation of `sepal_area` and `petal_area`.
- **Old vs New Models**:
  - Logistic Regression (Old)
  - Decision Tree (New)
  - Compare accuracies, classification reports, and confusion matrices.
- **Best Model Auto-Save**: Automatically saves the model & scaler with higher accuracy to your Downloads folder.
- **Multi-Sample Predictions**: Enter or edit multiple samples and get predicted species.
- **Interactive Visualizations**:
  - Accuracy bar charts
  - Confusion matrices
  - Prediction distribution
  - Sepal Area vs Petal Area scatter plots (filtered by species)
- **User-Friendly Interface**: Fully built with Streamlit for interactive exploration.

## Installation

Make sure you have Python 3.8+ installed. Then install the required packages:

```bash
pip install streamlit pandas numpy matplotlib seaborn scikit-learn joblib

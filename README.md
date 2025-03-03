# 🤖 Machine Learning - Classification: Logistic Regression & Model Evaluation

## 📝 Overview
This notebook focuses on fundamental classification techniques in Machine Learning, particularly **Logistic Regression**. We explore its theoretical foundations, implement it from scratch, and evaluate its performance on various datasets.

## 🎯 Objectives
- Understand the mathematical formulation of **Logistic Regression**.
- Implement **Gradient Descent-based Logistic Regression** from scratch.
- Evaluate classification performance using **confusion matrices, accuracy, precision, recall, and F1-score**.
- Generate and analyze decision boundaries for visualizing model predictions.

## 📦 Dependencies & Installation
Ensure the following libraries are installed before running the notebook:
```bash
pip install numpy matplotlib scikit-learn
```

## 🔑 Key Components
### 1️⃣ Logistic Regression Implementation
- **Sigmoid Activation Function** ➝ Converts linear predictions into probabilities.
- **Gradient Descent Optimization** ➝ Adjusts weights to minimize the loss function.
- **Binary Classification** ➝ Predicting two-class outcomes using probability thresholds.

### 2️⃣ Model Training & Evaluation
- **Data Generation & Preprocessing** ➝ Creating synthetic datasets for classification.
- **Confusion Matrix Analysis** ➝ Evaluating TP, FP, TN, FN to assess model performance.
- **Performance Metrics** ➝ Calculating accuracy, precision, recall, and F1-score.

### 3️⃣ Decision Boundary Visualization
- **Plotting Class Separation** ➝ Understanding how the model partitions input space.
- **Effect of Hyperparameters** ➝ Observing learning rate and iterations on decision boundaries.

## 📂 Metadata Files
- **Generated metadata files** store model weights, training statistics, and test results.
- These files facilitate reproducibility and further fine-tuning without retraining.

## 🚀 Execution Steps
1. Ensure all dependencies are installed and correctly configured.
2. Run all cells sequentially to train the Logistic Regression model.
3. Evaluate the model’s accuracy using confusion matrices and performance metrics.
4. Use stored metadata files for further experiments and visualization.

## ⚠️ Notes
- **Python & NumPy-based Implementation** ➝ No external ML libraries are used for model training.
- **Ensure all cells are executed before submission** to maintain consistency.
- Logistic Regression is a strong baseline classifier but may struggle with **non-linearly separable data**.

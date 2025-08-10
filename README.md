 Task 4: Logistic Regression Binary Classification

Objective
Build a binary classifier using **Logistic Regression** to predict whether a tumor is malignant or benign using the **Breast Cancer Wisconsin dataset**.

 Dataset
- **Source**: scikit-learn's built-in dataset
- **Features**: 30 numeric measurements of cell nuclei
- **Target**: 0 = malignant, 1 = benign

 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn

Steps Performed
1. **Load Data**: Imported dataset from Kaggle.
2. **Train/Test Split**: 80% training, 20% testing.
3. **Feature Scaling**: Standardized features for better performance.
4. **Model Training**: Fitted a Logistic Regression model.
5. **Evaluation**: Used confusion matrix, classification report, precision, recall, ROC-AUC.
6. **Visualization**:
   - ROC Curve
   - Sigmoid function
7. **Threshold Tuning**: Showed how changing decision threshold affects precision & recall.

 Evaluation Metrics
- **Confusion Matrix**: Shows correct/incorrect predictions.
- **Precision**: Measures accuracy of positive predictions.
- **Recall**: Measures coverage of actual positives.
- **ROC-AUC**: Measures model's ability to distinguish between classes.

Key Learnings
- Logistic Regression is suitable for binary classification.
- Sigmoid function maps linear output to probability.
- Threshold tuning allows prioritizing precision or recall.

 How to Run
1. Open `Google Colab`.
2. Upload this notebook or copy the code.
3. Run all cells.
4. View results & plots.
**Author**: Your Name  
**Date**: YYYY-MM-DD

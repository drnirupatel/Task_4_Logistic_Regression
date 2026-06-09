# Task 4: Classification with Logistic Regression

## Objective
Build a binary classification model using Logistic Regression.

## Dataset
Breast Cancer Wisconsin Dataset

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Performed
1. Loaded the dataset.
2. Removed unnecessary columns.
3. Encoded the target variable.
4. Split data into training and testing sets.
5. Standardized numerical features.
6. Trained a Logistic Regression model.
7. Evaluated performance using:
   - Confusion Matrix
   - Precision
   - Recall
   - F1-Score
   - ROC-AUC Score
8. Performed threshold analysis.

## Results

### Confusion Matrix
[[70, 1],
 [2, 41]]

### Classification Metrics

| Metric | Value |
|----------|----------|
| Accuracy | 97% |
| Precision | 0.98 |
| Recall | 0.95 |
| F1-Score | 0.96 |
| ROC-AUC | 0.9974 |

## Conclusion

The Logistic Regression model achieved excellent classification performance with 97% accuracy and a ROC-AUC score of 0.9974. The model effectively distinguished between malignant and benign tumors, making it suitable for binary classification tasks.

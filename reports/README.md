1. Objective

To predict whether an individual’s annual income is <=50K or >50K using demographic and employment-related features from the Census Income dataset.

2. Dataset

Source: Kaggle – Income dataset

Total samples: ~8792 (for testing)
[Actual total samples : 45957]

Features: 14 original (after encoding → ~97 columns)

Target: income (<=50K or >50K)

3. Model Used

Logistic Regression (baseline classification model)

4. Results

Accuracy: ~X% (replace with your accuracy score)

Confusion Matrix:

True Negatives (Correct <=50K) = 6228 

True Positives (Correct >50K) = 1204

False Negatives (missed high-income) = 900

False Positives (wrongly predicted high-income) =460

Classification Report (precision, recall, f1-score per class)

5. Insights

The model predicts low-income (<=50K) more accurately than high-income (>50K) because the dataset is imbalanced (more people earn <=50K).

Precision/Recall values show where the model struggles (usually recall for >50K is lower).

Logistic Regression is a good baseline, but more powerful models (Random Forest, XGBoost) could improve performance.

6. Conclusion

Logistic Regression achieves decent accuracy but struggles with the minority class (>50K).

Future work: try advanced models, feature scaling, and balancing techniques (SMOTE, class weights).

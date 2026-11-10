# Breast Cancer Classification using Machine Learning

- **Problem:** Predict whether a tumour is malignant or benign from cell nucleus measurements.
- **Dataset:** Breast Cancer Wisconsin (Diagnostic), 569 samples, 30 features.
- **Model:** Random Forest Classifier (80/20 train-test split, random_state=42).
- **Result:** 96.5% accuracy on the test set. The model correctly identified 40 of 43 malignant cases (3 missed) and 70 of 71 benign cases (1 false alarm).
- **Key finding:** The most important features were worst area, worst concave points and mean concave points. This fits the biology: cancerous nuclei tend to be larger and have more irregular, indented outlines.
- **Tools:** Python, pandas, scikit-learn, Google Colab.

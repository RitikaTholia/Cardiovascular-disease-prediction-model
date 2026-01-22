# Heart Disease Prediction

This project implements multiple machine learning models to predict the presence of heart disease based on clinical and diagnostic data. The dataset includes patient attributes such as age, cholesterol levels, blood pressure, ECG results, and more. Models are evaluated using accuracy, precision, recall, F1-score, sensitivity, specificity, ROC curves, and AUC.

## Project Workflow

1. **Importing Libraries**  
   Essential Python libraries for data analysis, visualization, and machine learning are imported.

2. **Importing the Dataset**  
   The dataset is loaded and preprocessed for analysis.

3. **Dataset Information (Pandas Profiling)**  
   Exploratory data analysis is performed using Pandas Profiling to understand feature distributions and correlations.

4. **Splitting the Train & Test Datasets**  
   Data is split into training and testing sets for model evaluation.

5. **Feature Scaling and Feature Selection**  
   Continuous variables are standardized, and categorical variables are encoded. Feature correlations are analyzed to identify important predictors.

---

## Models Implemented

### Random Forest Classifier
- Training and testing data preparation  
- Building a decision tree from the ensemble  
- Confusion matrix evaluation  
- Sensitivity and specificity calculation  
- ROC curve and accuracy assessment  

### Logistic Regression
- Training data preparation  
- Model prediction  
- Confusion matrix evaluation  
- Sensitivity and specificity calculation  
- ROC curve, accuracy, and AUC evaluation  

### K-Nearest Neighbors (KNN)
- Feature selection  
- Data processing and scaling  
- ROC curve and scoring evaluation  

### Artificial Neural Network (ANN)
- Building the ANN architecture  
  - Input layer  
  - Hidden layers  
  - Output layer  
- Training the ANN on the training set  
- Predictions and evaluation  
- Confusion matrix and accuracy evaluation  
- Sensitivity and specificity calculation  

---

## Evaluation Metrics

- **Accuracy**: Overall correctness of predictions  
- **Precision**: Correct positive predictions out of all predicted positives  
- **Recall (Sensitivity)**: Correct positive predictions out of all actual positives  
- **Specificity**: Correct negative predictions out of all actual negatives  
- **F1 Score**: Harmonic mean of precision and recall  
- **ROC Curve**: Graphical representation of sensitivity vs. specificity  
- **AUC (Area Under Curve)**: Single-number summary of ROC performance  

---

## Results Summary

| Model              | Accuracy | Precision | Recall | F1 Score | AUC   |
|--------------------|----------|-----------|--------|----------|-------|
| Random Forest      | 0.87     | 0.88      | 0.88   | 0.88     | 0.93  |
| Logistic Regression| 0.80     | 0.86      | 0.75   | 0.80     | 0.90  |
| KNN                | 0.83     | 0.85      | 0.85   | 0.85     | 0.90  |
| ANN                | 0.84     | 0.84      | 0.84   | 0.84     | 0.91  |

---

## Conclusion

The models demonstrate strong predictive ability, with Random Forest and ANN achieving the highest performance. Sensitivity and specificity values indicate balanced detection of both positive and negative cases. This project highlights the effectiveness of ensemble methods and neural networks in medical diagnosis tasks.

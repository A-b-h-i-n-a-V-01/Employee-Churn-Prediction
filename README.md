# Employee Churn Prediction

## Overview

This machine learning project predicts whether an employee is likely to leave a company based on factors such as satisfaction level, evaluation score, salary, department, and work history.

The project demonstrates a complete machine learning workflow including data cleaning, missing value handling, feature encoding, feature scaling, model training, and performance evaluation.

---

## Dataset Features

| Feature | Description |
|----------|-------------|
| satisfaction | Employee satisfaction level |
| evaluation | Last evaluation score |
| number_of_projects | Number of projects handled |
| average_montly_hours | Average monthly working hours |
| time_spend_company | Years spent in the company |
| work_accident | Work accident history |
| promotion | Promotion in the last 5 years |
| department | Employee department |
| salary | Salary level |
| churn | Target variable (0 = Stayed, 1 = Left) |

---

## Project Workflow

1. Load and explore the dataset
2. Handle missing values
3. Perform data visualization
4. Encode categorical features
5. Split dataset into training and testing sets
6. Apply feature scaling
7. Train classification models
8. Evaluate and compare model performance

---

## Machine Learning Models Used

### Logistic Regression
- Baseline classification model
- Evaluated before and after scaling

### K-Nearest Neighbors (KNN)
- Tested multiple K values
- Selected optimal K based on accuracy

### Support Vector Machine (SVM)
- Linear Kernel
- Polynomial Kernel
- RBF Kernel

### Decision Tree Classifier
- Entropy criterion

### Random Forest Classifier
- Ensemble learning approach

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Project Structure

```
employee-churn-prediction/
│
├── day03_activity.py
├── churn-data-v2.csv
├── README.md
```

---

## Learning Outcomes

- Missing Value Handling
- Data Visualization
- Feature Encoding
- Feature Scaling
- Classification Algorithms
- Model Evaluation
- Model Comparison

---

## Author

**Abhinav Krishna C S**

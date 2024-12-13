# Heart Attack Detection Using Machine Learning

This repository contains a CSE422 machine learning course project on heart attack risk prediction. The project demonstrates a basic supervised learning workflow, including dataset preparation, exploratory inspection, model training, and performance evaluation.

The notebook uses a synthetic clinical-style dataset for educational purposes. It is designed to show how common patient-related attributes can be used in a binary classification task, where the goal is to predict whether a patient belongs to a higher-risk or lower-risk category.

## Project Objectives

- Prepare a structured dataset for a heart attack risk classification problem.
- Train simple machine learning models using standard preprocessing techniques.
- Evaluate model performance using accuracy, classification reports, and a confusion matrix.
- Demonstrate how a trained model can be used to make a prediction for a new patient record.

## Repository Contents

- `heart_attack_detection_ml.ipynb` - main notebook containing data generation, preprocessing, training, evaluation, and sample prediction.

## Models Used

- Logistic Regression
- Random Forest Classifier

## How to Run

Install the required Python packages:

```bash
pip install notebook pandas numpy scikit-learn matplotlib
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open `heart_attack_detection_ml.ipynb` and run the cells from top to bottom.

## Academic Note

This project is intended only for academic demonstration. The dataset is synthetic and the resulting models are not suitable for medical diagnosis or real clinical decision-making.

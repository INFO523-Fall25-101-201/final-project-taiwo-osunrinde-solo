[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21349298)
# project-final

Final project repo for INFO 523 - Summer 2025.

# Cancer Prediction in patients using Convolutional Neural Network, Logistic Regression, and Random Forest Algorithms
## Cancer Prediction Project

**Course:** INFO 523 - Data Mining and Discovery
**Author:** Taiwo Osunrinde
**Institution:** College of Information Science, University of Arizona.

---

## Abstract

Cancer is a group of diseases characterized by the uncontrolled growth and spread of abnormal cells, which can invade nearby tissues and metastasize to distant parts of the body. It remains one of the leading causes of death worldwide, with no definitive cure currently available. While researchers and medical oncologists continue to pursue curative therapies, early detection remains one of the most effective strategies for improving patient outcomes, as it enables timely intervention such as early chemotherapy.

This project focuses on developing a machine learning (ML) model capable of predicting the presence of cancer in patients using simulated hospital data. Three algorithms were explored: Convolutional Neural Networks (CNN), Logistic Regression (LR), and Random Forest (RF). The LR and RF models were integrated into a soft voting classifier pipeline, while a four-layer neural network was constructed for the CNN model.

The dataset was initially split into 80% training and 20% testing sets, with the training portion further divided into training and validation subsets (80/20). Both the CNN and voting classifier models were trained and evaluated, with the voting classifier achieving the best performance: 93% accuracy, 92% precision, 89% recall, and an F1-score of 90%. The best-performing model was then retrained using the full training dataset.
Finally, an interactive web dashboard was developed to deploy the model, providing medical practitioners with a user-friendly tool to assist in determining whether a patient may be diagnosed with cancer.

---

## Research Questions & Objectives

### Primary Objective
To build a machine learning model that accurately predicts the presence of **cancer** in patients.

### Key Questions
1.  What are the factors contributing to cancer development in these patients?
2. Which of these models will accurately predict the presence of cancer in these patients?

---

## Dataset

* **Source:** Kaggle(https://www.kaggle.com/datasets/rabieelkharoua/cancer-prediction-dataset )
* **Data:** This data contains medical information for 1500 patients
* **Major Features:** Age, Gender, BMI, Smoking, GeneticRisk, PhysicalActivity, AlcoholIntake, CancerHistory.

---

## Methodology & Results
### Methods
1. Data cleaning
2. Exploratory data Analysis
3. Feature importance and Engineering
4. Split data into train, test, and validation
5. Model development (CNN, Logistic Regression, and Random Forests)
6. Model testing and validation

### Modeling Approach
* **Model development:** **CNN, Random Forest Regressor, and Logistic Regression**.

### Key Results (Voting Classifier)
| Metric | Value | 
| :--- | :--- | 
| **Accuracy** | **0.93** |
| **Precision** | **0.92**  | 
| **Recall** | **0.89**  | 
| **f1_score** | **0.90** | 

### Top features
The model identified the most critical features impacting price:
1.  **Age** (Engineered Feature)
2.  **Smoking**
3.  **GeneticRisk**

---

## Deliverables

* **Quarto Website:** Full analysis, EDA, and methodology (HTML format).
* **Presentation:** 5-minute slide deck summarizing key insights (RevealJS format).
* **Model Artifact:** Trained model saved as `cancer_model.pkl`.
* **Code Repository:** Fully reproducible code including analysis notebooks (`Final_Project.ipynb`).

---

#### Disclosure:
Derived from the original data viz course by Mine Çetinkaya-Rundel @ Duke University

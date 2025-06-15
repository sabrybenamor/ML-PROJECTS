# ML-PROJECTS

This repository contains various machine learning projects focused on practical applications and learning experiences.

---

## Project 1: Student Mental Health During Online Learning

### Dataset

The first project utilizes a dataset sourced from Kaggle, comprising responses from students about their mental health status during the era of online learning. The data was collected through surveys and highlights a range of psychological and behavioral factors affected by remote education.

- **Dataset size:** 1,000 samples
- **Features:** 10 columns, including demographic details, lifestyle habits, and self-reported mental health indicators

This dataset is well-suited for:
- Exploratory Data Analysis (EDA)
- Data visualization
- Building predictive models to understand the impact of online education on student mental well-being

### Approach

For this project, I applied a logistic regression model using the `LogisticRegression` class from the `scikit-learn` library. Due to the limited dataset size (1,000 entries), the model achieved an accuracy of no more than 53%. This highlights the challenges of building predictive models with limited data and the importance of larger, more comprehensive datasets for reliable results.

---

## Project 2: Cancer Cell Classifier

### Overview of the Dataset

The second project uses the Breast Cancer Wisconsin (Diagnostic) dataset, which is commonly used for binary classification tasks in machine learning.

- **Instances:** 569 tumor samples
- **Features:** 30 attributes, including radius, texture, perimeter, and area of tumors
- **Labels:**
  - `0 (Malignant)`: Cancerous
  - `1 (Benign)`: Non-cancerous

We use these features to train and evaluate various machine learning models for cancer detection.

### Approach

In this project, I implemented and compared three different models for classifying tumor cells:

1. **Linear Regression Model (Keras API)**  
   - Built a neural network using the Keras API (TensorFlow backend) for binary classification.

2. **Logistic Regression (`LogisticRegression` from scikit-learn)**  
   - Applied the standard logistic regression algorithm as a baseline linear classifier.

3. **K-Nearest Neighbors Classifier (`KNeighborsClassifier` from scikit-learn)**  
   - Used a non-parametric KNN approach to classify tumor samples based on similarity to neighbors.

Model performances were evaluated and compared based on their accuracy scores on the test set.

---

Stay tuned for more machine learning projects and experiments in this repository!

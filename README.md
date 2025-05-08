

````markdown
# Machine Learning Internship Project

## Overview

🚀 **Machine Learning Internship at Saiket Systems**

This repository showcases my work during my **Machine Learning Internship** at **Saiket Systems**, where I worked on several projects related to **customer churn prediction** and **model evaluation**. The internship gave me hands-on experience with machine learning algorithms, model evaluation metrics, and data-driven decision-making.

## Table of Contents

- [Projects](#projects)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Models](#models)
- [Results](#results)
- [License](#license)

## Projects

### 1. Customer Churn Prediction

- Built machine learning models for predicting customer churn.
- Explored and implemented classification algorithms such as **Decision Trees**, **Logistic Regression**, and **Random Forest**.
- Evaluated model performance using key metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

### 2. Model Evaluation and Selection

- Used metrics like **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC** to evaluate various machine learning models.
- Focused on finding the best model that predicted customer churn with the highest accuracy and performance.

### 3. Data Visualization and Insights

- Leveraged Python libraries to create **graphs and visualizations** that helped provide a clearer understanding of model performance and data characteristics.

---

## Technologies Used

- **Python** – The primary language used to implement all the models and analysis.
- **Scikit-learn** – A library used for machine learning model implementation.
- **Matplotlib / Seaborn** – Libraries used for visualizing model performance and data insights.
- **Pandas** – Used for data manipulation and preparation.
- **Jupyter Notebooks** – Used for documenting and visualizing data science workflows.

---

## How to Run

1. **Clone this repository** to your local machine:

   ```
   git clone https://https://github.com/Stressed-by-a-mountain-of-codes/telecom_data_machine_learning
````

2. **Navigate** to the project directory:

   ```
   cd machine-learning-internship-project
   ```

3. **Install dependencies**:

   You can create a virtual environment and install the necessary dependencies using `pip`:

   ```
   pip install -r requirements.txt
   ```

4. **Run the notebook** for model training and evaluation:

   ```
   jupyter notebook
   ```

   Open the relevant Jupyter notebook (e.g., `1_data_preparation.ipynb`) to see the step-by-step implementation.

---

## Models

* **Logistic Regression Model**

  * A logistic regression model trained to predict customer churn with key metrics.
  * [Download Model](./models/logistic_regression_model.pkl)

* **Random Forest Model**

  * A random forest classifier to improve churn prediction performance.
  * [Download Model](./models/random_forest_model.pkl)

* **Decision Tree Model**

  * A decision tree classifier used for churn prediction and model evaluation.
  * [Download Model](./models/decision_tree_model.pkl)

---

## Results

### Model Evaluation Metrics:

| Model                   | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
| ----------------------- | -------- | --------- | ------ | -------- | ------- |
| **Logistic Regression** | 0.85     | 0.87      | 0.82   | 0.84     | 0.87    |
| **Random Forest**       | 0.88     | 0.90      | 0.84   | 0.87     | 0.89    |
| **Decision Tree**       | 0.83     | 0.85      | 0.78   | 0.81     | 0.84    |

* The **Random Forest** model outperformed others in most evaluation metrics, including **accuracy** and **ROC-AUC**.



# Breast Cancer Classification using Logistic Regression

A Machine Learning project that uses **Logistic Regression** to classify breast tumours as **Malignant (M)** or **Benign (B)** based on features extracted from digitized images of breast mass samples.

The project uses Python and Scikit-learn to perform data preprocessing, exploratory data analysis, feature scaling, model training, and performance evaluation.

## Project Overview

Breast cancer classification is a binary classification problem in which the objective is to predict whether a tumour is malignant or benign based on various numerical measurements.

This project implements a Logistic Regression model using the Breast Cancer Wisconsin (Diagnostic) dataset.

**Objectives:**
- Explore and understand the dataset.
- Perform data cleaning and preprocessing.
- Analyze the distribution of diagnosis categories.
- Standardize numerical features using StandardScaler.
- Train a Logistic Regression classification model.
- Evaluate model performance using classification metrics.

## Dataset

The project uses the Breast Cancer Wisconsin (Diagnostic) dataset.

- **Total observations:** 569
- **Features:** 30 numerical features
- **Target variable:** `diagnosis`
- **Classification type:** Binary Classification

**Target classes:**

| Class | Description |
|---|---|
| M | Malignant |
| B | Benign |

The dataset contains measurements such as:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

These measurements are provided as mean, standard error, and worst-value features.

## Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Seaborn** – Statistical data visualization
- **Scikit-learn** – Machine Learning and model evaluation
- **Jupyter Notebook** – Development environment

## Project Workflow

1. **Data Loading:** Load the dataset using Pandas.
2. **Data Exploration:** Examine dataset structure, data types, and statistical information.
3. **Data Cleaning:** Remove unnecessary columns and handle irrelevant data.
4. **Exploratory Data Analysis:** Visualize feature distributions and diagnosis categories.
5. **Feature Selection:** Separate independent variables (X) and the target variable (y).
6. **Feature Scaling:** Apply StandardScaler to standardize numerical features.
7. **Data Splitting:** Divide the dataset into training and testing sets.
8. **Model Training:** Train a Logistic Regression classifier.
9. **Prediction:** Predict diagnosis categories using the test dataset.
10. **Model Evaluation:** Evaluate performance using accuracy, precision, recall, and F1-score.

## Model: Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm used for classification problems.

It estimates the probability of a sample belonging to a particular class using the logistic (sigmoid) function.

The model predicts one of two possible outcomes:

- Malignant
- Benign

## Model Evaluation

The model is evaluated using the following metrics:

- **Accuracy:** Measures the overall percentage of correct predictions.
- **Precision:** Measures how many predicted positive cases are actually positive.
- **Recall:** Measures how many actual positive cases are correctly identified.
- **F1-Score:** Represents the harmonic mean of precision and recall.

### Recorded Results

The current notebook reports approximately **99% test accuracy** using a 70:30 train-test split.

The classification report also provides precision, recall, and F1-score for both classes.


## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/jithendra847/Cancer-Classification.git
```

### 2. Navigate to the project directory

```bash
cd Cancer-Classification
```

### 3. Create a virtual environment (optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Cancer.ipynb` and run the cells to explore the complete implementation.

## Project Structure

```text
Cancer-Classification/
│
├── Cancer.ipynb       # Main Jupyter Notebook
├── data.csv           # Breast cancer dataset
├── requirements.txt   # Project dependencies
└── README.md          # Project documentation
```

## Author

**Jithendra Yatam**

- GitHub: [@jithendra847](https://github.com/jithendra847)

---

If you find this project useful, feel free to ⭐ the repository!
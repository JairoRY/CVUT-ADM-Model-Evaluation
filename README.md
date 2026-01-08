# Model Evaluation and Data Mining

This repository contains materials for advanced data mining and model evaluation. The project was developed as part of the Data Mining Algorithms (ADM) course at the Czech Technical University (CVUT) in Prague, during an academic exchange from the Universitat Politècnica de Catalunya (UPC).

The primary focus of this tutorial is the application of machine learning techniques to predict outcomes from a bank marketing dataset, followed by a rigorous evaluation of the model performance using various metrics.

## Project Structure

The repository is organized into the following files:

**Notebooks**

* **ADM_T001_MODEL_EVALUATION.ipynb**: The main Jupyter Notebook containing data preprocessing, feature engineering, model training, and a detailed evaluation of performance metrics such as accuracy, precision, recall, and F1-score.

**Datasets**

* **bank-additional-full.csv**: A comprehensive dataset related to direct marketing campaigns of a Portuguese banking institution. The data is often used for classification tasks to predict whether a client will subscribe to a term deposit.

## Getting Started

### Prerequisites

To run the analysis, you will need a Python environment with the following libraries installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

```

### Usage

1. **Clone the repository:**
```bash
git clone https://github.com/JairoRY/CVUT-ADM-Tutorial-1.git
cd CVUT-ADM-Tutorial-1

```


2. **Launch the Jupyter Notebook:**
```bash
jupyter notebook ADM_T001_MODEL_EVALUATION.ipynb

```



## Analysis Overview

The project covers several critical steps in the data mining pipeline:

* **Data Exploration**: Initial analysis of the bank marketing data to understand distribution, missing values, and correlation between variables.
* **Preprocessing**: Handling categorical variables through encoding and scaling numerical features for optimal model performance.
* **Model Selection**: Implementing classification algorithms to address the business problem.
* **Evaluation**: Comparing models using confusion matrices, ROC curves, and cross-validation techniques to ensure robustness and reliability.

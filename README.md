# Data Preprocessing with Python

A practical collection of Python projects and Jupyter notebooks covering essential **Data Preprocessing Techniques** using Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

This repository demonstrates how to clean, transform, and prepare raw datasets for data analysis and machine learning. Each notebook focuses on a specific preprocessing technique, with practical examples using real-world datasets.

## 📌 Repository Overview

Data preprocessing is an essential step in the data analysis and machine learning workflow. Raw datasets often contain missing values, duplicate records, inconsistent data types, categorical variables, and outliers.

This repository provides hands-on practice with different techniques to identify and handle these issues and transform raw data into a structured and usable format.

### Topics Covered

- Finding and handling missing values
- Removing and imputing missing data
- Encoding categorical variables
- Detecting and handling outliers
- Feature scaling and normalization
- Removing duplicate records
- Replacing values and changing data types
- Function transformation
- Feature selection

## 📂 Repository Structure

```text
Data-Preprocessing/
│
├── Datasets/
│   ├── diabetes.csv
│   └── Loan.csv
│
├── 1-Finding-Null-Values.ipynb
├── 2-Dropping-Null-Values.ipynb
├── 3-Filling-Missing-Values.ipynb
├── 4-Imputing-Missing-Values-Using-ScikitLearn.ipynb
├── 5-One-Hot-Encoding.ipynb
├── 6-Label-Encoding.ipynb
├── 7-Ordinal-Encoding.ipynb
├── 8-Outlier.ipynb
├── 9-Outlier-Removal-Using-IQR.ipynb
├── 10-Outlier-Removal-Using-Z-Score.ipynb
├── 11-Feature-Scaling-(Standardization).ipynb
├── 12-Feature-Scaling-(Normalization).ipynb
├── 13-Handling-Duplicate-Data.ipynb
├── 14-Replacing-Data-&-Changing-DataType.ipynb
├── 15-Function-Transformation.ipynb
├── 16-Feature-Selection.ipynb
│
└── README.md
```

## 📚 Notebooks and Topics

The repository contains 16 Jupyter notebooks covering the following preprocessing techniques.

| # | Notebook | Description |
|---|---|---|
| 01 | Finding Null Values | Identifying missing values in a dataset using Pandas. |
| 02 | Dropping Null Values | Removing rows or columns containing missing values. |
| 03 | Filling Missing Values | Handling missing values using different filling techniques. |
| 04 | Imputing Missing Values Using Scikit-Learn | Applying Scikit-learn imputation techniques to handle missing data. |
| 05 | One-Hot Encoding | Converting categorical variables into binary columns. |
| 06 | Label Encoding | Converting categorical labels into numerical values. |
| 07 | Ordinal Encoding | Encoding categorical variables with an ordered relationship. |
| 08 | Outlier Detection | Identifying unusual observations in a dataset. |
| 09 | Outlier Removal Using IQR | Detecting and removing outliers using the Interquartile Range method. |
| 10 | Outlier Removal Using Z-Score | Identifying outliers using statistical Z-score values. |
| 11 | Feature Scaling (Standardization) | Standardizing numerical features using standard scaling. |
| 12 | Feature Scaling (Normalization) | Scaling numerical features to a common range. |
| 13 | Handling Duplicate Data | Identifying and removing duplicate records. |
| 14 | Replacing Data & Changing Data Type | Replacing values and converting columns into appropriate data types. |
| 15 | Function Transformation | Applying mathematical transformations to features. |
| 16 | Feature Selection | Selecting relevant features for data analysis and machine learning. |

## 🗂️ Datasets

The repository includes the following datasets for practical implementation:

| Dataset | Description |
|---|---|
| `diabetes.csv` | Diabetes dataset used for practicing data preprocessing techniques. |
| `Loan.csv` | Loan dataset used for practicing data cleaning and preprocessing techniques. |

Both datasets are stored in the `Datasets` directory.

## 🛠️ Technologies and Libraries

The following tools and Python libraries are used throughout this repository:

- **Python** – Programming language.
- **Jupyter Notebook** – Interactive environment for practical implementation.
- **Pandas** – Data manipulation and cleaning.
- **NumPy** – Numerical computing and array operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Scikit-learn** – Data preprocessing and machine learning utilities.

## ⚙️ Installation and Setup

Follow these steps to run the notebooks on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Data-Preprocessing.git
```

### 2. Navigate to the Project Directory

```bash
cd Data-Preprocessing
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open a Notebook

Open any `.ipynb` file and execute the cells sequentially to explore the corresponding preprocessing technique.

You can also open the notebooks directly in Visual Studio Code using the Jupyter extension.

## 🎯 Learning Objectives

Through this repository, I aim to:

- Understand the importance of data preprocessing in data analysis and machine learning.
- Identify and handle missing values in datasets.
- Apply different categorical encoding techniques.
- Detect and manage outliers using statistical methods.
- Understand the differences between standardization and normalization.
- Clean datasets by handling duplicate records and inconsistent data types.
- Apply mathematical transformations to numerical features.
- Understand feature selection and its role in improving machine learning workflows.
- Develop practical Python skills for working with real-world datasets.


## 👨‍💻 Author

**Riaz Uddin**

Electrical Engineering Graduate | Data Analytics | Python | SQL | Power BI | Machine Learning | Data Science

- GitHub: [github.com/Riaz0647951](https://github.com/Riaz0647951)
- LinkedIn: [linkedin/in/riaz-ud-din-0918a3271/](https://www.linkedin.com/in/riaz-ud-din-0918a3271/)

## ⭐ Support

If you find this repository helpful for learning data preprocessing, consider giving it a ⭐ on GitHub.

Your feedback and suggestions are always welcome!

---

*This repository is part of my continuous learning journey in Data Analytics, Data Science, and Machine Learning.*

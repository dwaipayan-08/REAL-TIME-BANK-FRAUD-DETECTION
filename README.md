# 💳 Real-Time Banking Fraud Detection – Exploratory Data Analysis

## 1. Introduction
This project focuses on analysing credit card transaction data to understand the patterns and behaviour of fraudulent and non-fraudulent transactions.
The main aim is to explore banking transaction data, identify unusual transaction patterns, and understand which features may be associated with fraudulent activities.Using Python and different data analysis and visualization libraries, I have performed Exploratory Data Analysis (EDA) on a credit card fraud detection dataset.This project demonstrates how data analysis and visualization techniques can help in understanding potential fraud indicators in banking transactions.

## 2. Project Objectives
The main objectives of this project are:
- To explore and understand banking transaction data.
- To identify the distribution of fraudulent and legitimate transactions.
- To analyse transaction amount patterns.
- To compare fraudulent and non-fraudulent transactions.
- To examine transaction time-based patterns.
- To identify important features associated with fraudulent activities.
- To visualize transaction patterns using statistical and graphical techniques.
- To apply Principal Component Analysis (PCA) for two-dimensional visualization.

## 3. Dataset Description

**Dataset:** Credit Card Fraud Detection Dataset

The dataset contains **284,807 transactions** and **31 columns**.

| Attribute | Description |
|---|---|
| Time | Time elapsed between transactions |
| V1–V28 | Anonymized numerical transaction features |
| Amount | Transaction amount |
| Class | Transaction classification |

### Class Representation

- `0` – Non-fraudulent transaction
- `1` – Fraudulent transaction

### Dataset Distribution

- Non-fraudulent transactions: 284,315
- Fraudulent transactions: 492
- Total transactions: 284,807

The dataset is highly imbalanced because fraudulent transactions represent a very small percentage of the total records.

## 4. Technologies and Libraries Used

The project uses the following technologies and Python libraries:

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Plotly | Interactive visualizations |
| Scikit-learn | Feature scaling and PCA |
| Jupyter Notebook | Running the analysis |

## 5. Exploratory Data Analysis

The following analysis has been performed:

### 5.1 Data Inspection
- Examined the dataset structure.
- Checked rows, columns and data types.
- Checked missing values.
- Generated descriptive statistical summaries.

### 5.2 Class Distribution Analysis

Compared fraudulent and non-fraudulent transactions using a bar chart to understand the imbalance between the two classes.

### 5.3 Transaction Amount Distribution

Used histograms and density plots to understand the distribution of transaction amounts.

### 5.4 Fraud vs. Non-Fraud Comparison

Compared transaction amounts and time patterns using box plots and density plots.

### 5.5 Correlation Analysis

Created a correlation matrix using a heatmap to identify relationships between transaction features and the target variable (`Class`).

### 5.6 Potential Fraud Indicators

Explored unusual transaction amounts, selected transaction time windows and anonymized features to identify patterns associated with fraudulent transactions.

### 5.7 PCA Visualization

Applied Principal Component Analysis (PCA) to reduce the transaction features into two principal components.

A scatter plot was used to visualize the resulting representation and explore patterns between fraudulent and non-fraudulent transactions.

## 6. Key Findings

Some important observations from the exploratory analysis include:

1. The dataset is highly imbalanced, with fraudulent transactions accounting for a very small proportion of all transactions.
2. Transaction amount distributions show differences between fraudulent and legitimate transactions.
3. Certain anonymized features have stronger correlations with the fraud classification.
4. Features such as V10, V12 and V14 show notable negative values in fraudulent transaction records.
5. PCA provides a simplified two-dimensional representation of the transaction data and helps visualize possible patterns.

These findings provide a better understanding of the characteristics of fraudulent transactions.

## 7. Project Structure

```text
REAL-TIME-BANKING-FRAUD/
│
├── Mini_project.pdf
├── PRACTICEMINIPROJECT.tex
├── README.md
├── requirements.txt
├── creditcard.csv
│
├── output_7_0.png
├── output_8_0.png
├── output_9_0.png
├── output_10_0.png
├── output_11_0.png
├── output_12_0.png
├── output_16_0.png
├── output_26_1.png
├── output_27_1.png
└── output_28_1.png
```

*Note: The notebook file containing the EDA code should also be placed in the project directory.*

## 8. Installation and Requirements

### Step 1: Clone or Download the Repository

Download the project files to your computer.

### Step 2: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 3: Activate the Virtual Environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

**Ubuntu/Linux:**

```bash
source venv/bin/activate
```

### Step 4: Install Required Libraries

```bash
pip install -r requirements.txt
```

Alternatively, install the libraries directly:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter ipykernel
```

## 9. How to Run the Project

Follow these steps to perform the analysis:

1. Download or clone the project repository.
2. Download the Credit Card Fraud Detection dataset.
3. Place the dataset file (`creditcard.csv`) inside the project working directory.
4. Create and activate the Python virtual environment.
5. Install the required Python libraries.
6. Open the project notebook using Jupyter Notebook or Google Colab.
7. Run the notebook cells sequentially.
8. Explore the generated charts, graphs and analysis results.

To launch Jupyter Notebook, run:

```bash
jupyter notebook
```

## 10. Conclusion

Through this project, I have explored credit card transaction data to understand the characteristics and patterns of fraudulent and non-fraudulent banking activities.

The analysis helped me understand how statistical techniques, correlation analysis, data visualization and dimensionality reduction can be used to explore potential fraud indicators.

Working on this project also provided practical experience with Python, data analysis libraries, Exploratory Data Analysis and Principal Component Analysis.

**Project Status:** This project currently focuses on Exploratory Data Analysis and visualization. It does not yet include a trained fraud classification model or a live real-time banking transaction monitoring system.

## 11. Future Scope

This project can be extended in several ways:

- Develop machine learning models for fraud detection.
- Implement algorithms such as Logistic Regression, Random Forest, Decision Tree and XGBoost.
- Handle class imbalance using SMOTE and other suitable techniques.
- Evaluate model performance using Precision, Recall, F1-Score and ROC-AUC.
- Develop a real-time fraud detection system to analyse incoming banking transactions.
- Build a user-friendly dashboard to display fraud detection results.

## Author

**Dwaipayan Ghosh**

## Real-Time Banking Fraud -- Exploratory Data Analysis
## 1. Introduction
In this project, I have explored banking transaction data to understand
fraudulent and non-fraudulent transaction patterns. The main objective
of this study is to identify unusual transaction behaviour and
understand which factors may be associated with fraudulent banking
activities.

I have used Python and various data analysis and visualization libraries
to perform Exploratory Data Analysis (EDA) on the credit card
transaction dataset.

Through this project, I aim to understand how data analysis can help in
identifying potential fraud indicators in banking transactions.
## 2. Project Objectives
The main objectives of this project are:
- To explore and understand banking transaction data.
- To identify the distribution of fraudulent and non-fraudulent
  transactions.
- To analyse transaction amount patterns.
- To compare the behaviour of fraudulent and legitimate transactions.
- To examine transaction time-based patterns.
- To identify important features associated with fraudulent
  transactions.
- To visualize transaction patterns using different statistical and
  graphical techniques.
- To use PCA for visualizing transaction patterns in a reduced
  two-dimensional space.
## 3. Dataset Description
For this project, I have used the Credit Card Fraud Detection dataset.

The dataset contains 284,807 transactions with 31 columns.

  Attribute   Description
  Time        Time elapsed between transactions
V1--V28     Anonymized numerical transaction features
Amount      Transaction amount
Class       Transaction classification

Class representation: - 0 -- Non-fraudulent transaction - 1 --
Fraudulent transaction

The dataset contains 284,315 non-fraudulent transactions and 492
fraudulent transactions.
## 4. Technologies and Libraries Used
I have used the following technologies and Python libraries:
- Python -- Main programming language.
- Pandas -- Data manipulation and analysis.
- NumPy -- Numerical operations.
- Matplotlib -- Data visualization.
- Seaborn -- Statistical data visualization.
- Plotly -- Interactive visualizations.
- Scikit-learn -- Feature scaling and Principal Component Analysis
  (PCA).
## 5. Exploratory Data Analysis (EDA)
I have performed the following analysis in this project:
## 5.1 Data Inspection
- Examined the dataset structure.
- Checked the number of rows and columns.
- Analysed data types.
- Checked for missing values.
- Generated descriptive statistical summaries.
## 5.2 Class Distribution Analysis
Compared the number of fraudulent and non-fraudulent transactions using
a bar chart.

This helped me understand the imbalance between the two transaction
classes.
## 5.3 Transaction Amount Distribution
Analysed the distribution of transaction amounts using histograms and
density plots to understand the overall transaction behaviour.
## 5.4 Fraud vs. Non-Fraud Comparison
Compared fraudulent and non-fraudulent transactions based on: -
Transaction amounts. - Transaction time patterns.

Used box plots and density plots to identify differences in transaction
behaviour.
## 5.5 Correlation Analysis
Created a correlation matrix using a heatmap to understand relationships
between different transaction features and the target variable
(Class).

This helped identify features that have stronger positive or negative
correlations with fraudulent transactions.
## 5.6 Identification of Potential Fraud Indicators
Explored unusual transaction amounts and transactions occurring during
selected time windows.

Also examined the relationship between important anonymized features and
fraudulent transactions.
## 5.7 PCA Visualization
Applied Principal Component Analysis (PCA) to reduce the transaction
data into two principal components.

Visualized the resulting data using a scatter plot to explore possible
patterns and clusters between fraudulent and non-fraudulent
transactions.
## 6. Key Findings
From the exploratory analysis, I observed the following:
1. The dataset is highly imbalanced, with fraudulent transactions
   representing a very small proportion of all transactions.
2. There are noticeable differences in the distribution of transaction
   amounts between the two classes.
3. Certain anonymized features show stronger correlations with the
   fraud classification.
4. Features such as V10, V12 and V14 show notable negative values in
   fraudulent transaction records.
5. PCA provides a two-dimensional representation that helps visualize
   the overall transaction patterns.
These observations provide useful insights into the characteristics of
fraudulent transactions.
## 7. Project Structure
REAL-TIME-BANKING-FRAUD/
│
├── Mini_project.pdf
├── PRACTICEMINIPROJECT.tex
├── README.md
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

## 8. Installation and Requirements
First, install Python and the required libraries.

Run the following command:
pip install pandas numpy matplotlib seaborn plotly scikit-learn
9. How to Run the Project
1. Download or clone this repository.
2. Download the Credit Card Fraud Detection dataset.
3. Place creditcard.csv in the project working directory.
4. Install the required Python libraries.
5. Open the project notebook in Jupyter Notebook or Google Colab.
6. Run the cells sequentially to perform the analysis and generate
   visualizations.
## 10. Conclusion
Through this project, I have explored credit card transaction data to
understand the characteristics of fraudulent and non-fraudulent banking
activities.

The analysis helped me understand how statistical analysis, correlation
techniques and data visualization can be used to identify potential
fraud indicators.

This project has also helped me gain practical experience in
Python-based data analysis, Exploratory Data Analysis and dimensionality
reduction using PCA.

Note: This project currently focuses on exploratory data analysis
and visualization. It does not yet implement a trained fraud
classification model or a live real-time banking transaction monitoring
system.
## 11. Future Scope
In the future, I would like to extend this project by:
- Developing machine learning models for fraud detection.
- Applying algorithms such as Logistic Regression, Random Forest,
  Decision Tree and XGBoost.
- Handling class imbalance using SMOTE or other suitable techniques.
- Evaluating model performance using Precision, Recall, F1-Score and
  ROC-AUC.
- Developing a real-time fraud detection system capable of analysing
  incoming banking transactions.
  ## Author
  Dwaipayan Ghosh

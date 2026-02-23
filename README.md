**E-commerce Review Sentiment Analysis**
This repository contains a Jupyter Notebook that performs sentiment classification on e-commerce product reviews using a machine learning approach.

🚀 **Overview**
The project explores the relationship between customer review text and sentiment labels. It focuses on data preprocessing via label encoding and Text Vectorization .it also evaluates the performance using linear regression and logistic regression.

🛠️ **Tech Stack**
Language: Python

Libraries: Pandas, NumPy, Scikit-learn

Environment: Jupyter Notebook / Google Colab

📊 **Dataset**
File: ecommerce-product-reviews.csv

Size: 5,000 entries

Features: - review: Textual feedback from customers.

label: Sentiment category (Positive, Neutral, Negative).

⚙️ **Workflow**
Data Cleaning: Handled using Pandas and filtered warnings for a clean output.

Preprocessing: - Utilized LabelEncoder  and text Vectorization to transform both review text and sentiment labels into numerical formats.

Modeling:

Implemented linear_model.LinearRegression and linear_model.LogisticRegression to predict sentiment scores.

Evaluation:

The model was assessed using the .score() method, providing a baseline for future NLP optimization (e.g., TF-IDF, Word2Vec, or Random Forest).


Install dependencies: pip install pandas scikit-learn numpy

Run E_commerce_Review_Model_Analysis.ipynb.

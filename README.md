\# Customer Support Ticket Classification



An NLP-based machine learning project that automatically classifies customer support tickets into their appropriate \*\*ticket category\*\* and \*\*priority level\*\* using TF-IDF and Logistic Regression.



\## Project Overview



Customer support teams receive a large number of tickets every day. Manually categorizing and prioritizing these tickets can be time-consuming.



This project uses Natural Language Processing (NLP) to analyze customer support ticket text and predict:



\- Ticket Category

\- Ticket Priority



\## Dataset



\- Total Tickets: 8,469

\- Features: 17

\- Ticket Categories: 5

\- Ticket Priorities: 4



\### Ticket Categories



\- Billing inquiry

\- Cancellation request

\- Product inquiry

\- Refund request

\- Technical issue



\### Ticket Priorities



\- Critical

\- High

\- Medium

\- Low



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- Matplotlib

\- Seaborn

\- NLP

\- TF-IDF Vectorization

\- Logistic Regression

\- Jupyter Notebook



\## Machine Learning Approach



\### 1. Data Loading

The customer support ticket dataset was loaded and explored using Pandas.



\### 2. Data Analysis

Dataset structure, missing values, duplicate records, ticket categories, priorities and relationships between features were analyzed.



\### 3. Text Preparation

Ticket Subject and Ticket Description were combined into a single text feature.



\### 4. TF-IDF Vectorization

TF-IDF was used to convert customer support text into numerical features.



\- Maximum Features: 5,000

\- Training Samples: 6,775

\- Testing Samples: 1,694



\### 5. Model Training



Two Logistic Regression models were trained:



1\. Ticket Category Classification

2\. Ticket Priority Classification



\## Model Performance



| Model | Accuracy |

|---|---:|

| Ticket Category Classification | 20.96% |

| Ticket Priority Classification | 25.91% |



The baseline accuracy is approximately:



\- Category: 20.00% for 5 classes

\- Priority: 25.00% for 4 classes



The project also includes confusion matrices and classification reports for evaluating model performance.



\## Project Structure



```text

Customer\_Support\_Ticket\_Classification/

│

├── Customer\_Support\_Ticket\_Classification.ipynb

├── README.md

├── requirements.txt

└── .gitignore


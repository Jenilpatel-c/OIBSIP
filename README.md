📊 OIBSIP Data Analytics Projects

Welcome to my Data Analytics project repository created as part of the Oasis Infobyte Internship Program (OIBSIP).
This repository contains multiple real-world data analytics and machine learning projects implemented using Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn in Jupyter Notebook.

The projects focus on:

Exploratory Data Analysis (EDA)
Data Cleaning & Preprocessing
Customer Segmentation
Sentiment Analysis using NLP
Machine Learning Models
House Price Prediction
🛠️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
NLTK
Kaggle Dataset
📁 Repository Structure
├── Jenil_Task1.ipynb
├── Jenil_Task2.ipynb
├── Jenil_Task3.ipynb
├── Jenil_Task4.ipynb
├── Jenil_Task5.ipynb
└── README.md

📌 Task 1 – Exploratory Data Analysis on Retail Sales Data
📖 Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to discover customer purchasing patterns and business insights.

🎯 Objectives
Analyze retail sales trends
Perform statistical analysis
Clean and preprocess data
Visualize important business insights
🔍 Key Operations
Data loading using Pandas
Missing value handling
Duplicate removal
Statistical analysis
Data visualization using Matplotlib and Seaborn
📚 Libraries Used
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

📌 Task 2 – Customer Segmentation Analysis
📖 Project Overview

This project analyzes customer behavior and purchasing patterns using customer segmentation techniques.

🎯 Objectives
Study customer demographics
Analyze customer spending habits
Understand purchasing behavior
Generate business insights
🔍 Key Operations
Data cleaning
Customer data preprocessing
Statistical analysis
Visualization of customer trends
📚 Libraries Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

📌 Task 3 – Data Cleaning on NYC Airbnb Dataset
📖 Project Overview

This project demonstrates real-world data cleaning and preprocessing using the NYC Airbnb Open Data dataset.

🎯 Objectives
Handle missing values
Remove duplicates
Analyze dataset quality
Prepare clean dataset for analytics
🔍 Key Operations
Missing value treatment
Duplicate record removal
Data consistency checks
Data preprocessing
📚 Libraries Used
import pandas as pd
import numpy as np

📌 Task 4 – Twitter Sentiment Analysis using NLP
📖 Project Overview

This project focuses on performing Sentiment Analysis on Twitter data using Natural Language Processing (NLP) and Machine Learning techniques. The goal is to classify tweets into positive, neutral, and negative sentiments using TF-IDF Vectorization and Logistic Regression.

🎯 Objectives
Load and explore Twitter sentiment dataset
Clean and preprocess tweet text data
Perform NLP preprocessing techniques
Convert text into numerical vectors using TF-IDF
Train a machine learning model for sentiment classification
Evaluate model performance using accuracy and confusion matrix
🔍 Key Operations Performed
Data loading using Pandas
Missing value handling
Text preprocessing and cleaning
Lowercasing text
Removing punctuation and stopwords
Lemmatization using NLTK
TF-IDF feature extraction
Train-test splitting
Logistic Regression model training
Model evaluation using:
Accuracy Score
Classification Report
Confusion Matrix Visualization
📚 Libraries Used
import pandas as pd
import numpy as np
import re
import nltk
import matplotlib.pyplot as plt
import seaborn as sns
from nltk.corpus import stopwords
from nltk.stem import WordNetLemmatizer
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report, accuracy_score, confusion_matrix

📌 Task 5 – House Price Prediction using Linear Regression
📖 Project Overview

This project builds a Machine Learning model to predict house prices using Linear Regression. The project includes data preprocessing, handling categorical variables, feature scaling, model training, evaluation, and visualization.

🎯 Objectives
Predict house prices based on housing features
Analyze relationships between housing variables
Convert categorical data into numerical format
Train and evaluate a Linear Regression model
Visualize actual vs predicted house prices
🔍 Key Operations Performed
Dataset loading and exploration
Missing value checking
One-hot encoding of categorical variables
Feature scaling using StandardScaler
Train-test data splitting
Linear Regression model training
Model prediction on test data
Model evaluation using:
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared Score (R²)
Visualization of predicted vs actual prices using scatter plot
📚 Libraries Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import mean_squared_error, r2_score


📈 Learning Outcomes
Through these projects, I learned:

Data Cleaning Techniques
Exploratory Data Analysis
Natural Language Processing (NLP)
Machine Learning Algorithms
Logistic Regression
Linear Regression
TF-IDF Vectorization
Feature Engineering
Model Evaluation
Data Visualization
Real-world Dataset Handling
🚀 How to Run the Projects
1️⃣ Clone the Repository
git clone <your-github-repository-link>
2️⃣ Open Jupyter Notebook
jupyter notebook
3️⃣ Run the Notebook Files


📚 Dataset Sources
Retail Sales Dataset
iFood Customer Dataset
NYC Airbnb Open Data Dataset
Twitter Sentiment Dataset
Housing Price Dataset

👨‍💻 Author
Jenil Patel
Data Analytics Intern – OIBSIP

⭐ Conclusion
These projects demonstrate practical implementation of:

Data preprocessing
Exploratory data analysis
Machine learning
Natural language processing
Regression analysis
Classification models
Real-world business analytics

They helped strengthen my understanding of Python-based Data Analytics and Machine Learning workflows.

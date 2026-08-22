# Zomato-Restaurant-Review-Sentiment-Analysis
Machine learning and NLP project for sentiment classification of Zomato restaurant reviews using TF-IDF and classification algorithms.

## Project Overview
This project applies Machine Learning and Natural Language Processing (NLP) techniques to analyze Zomato restaurant reviews and classify customer sentiment as Positive or Negative.

The project includes data exploration, data cleaning, text preprocessing, exploratory data analysis, hypothesis testing, feature engineering, model building, hyperparameter tuning, model evaluation, and model explainability.

## Dataset
The project uses two datasets:

- Zomato Restaurant names and Metadata.csv
- Zomato Restaurant reviews.csv

The datasets contain restaurant information, customer reviews, ratings, cuisines, cost information, and other restaurant-related attributes.

## Machine Learning Approach
Customer review text was processed and converted into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency).

Multiple classification models were evaluated, including:

- Logistic Regression
- Naive Bayes
- Linear Support Vector Machine (SVM)

The final prediction model selected was **Logistic Regression with TF-IDF features**, considering its overall classification performance and interpretability.

## Model Explainability
The coefficients of the Logistic Regression model were used to identify influential TF-IDF features.

Positive coefficients indicate words or phrases contributing toward positive sentiment predictions, while negative coefficients indicate features contributing toward negative sentiment predictions.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF
- Google Colab

## Project Workflow
1. Data Understanding
2. Data Wrangling
3. Exploratory Data Analysis
4. Data Visualization
5. Hypothesis Testing
6. Text Preprocessing
7. TF-IDF Feature Extraction
8. Machine Learning Model Building
9. Hyperparameter Tuning
10. Model Evaluation
11. Model Explainability
12. Model Saving and Prediction on Unseen Reviews

## Conclusion
The project demonstrates how NLP and machine learning can automatically classify customer sentiment from restaurant reviews. The resulting model can help restaurants understand customer feedback and identify areas for improving customer experience.


# News Article Multiclass Classification Using NLP

** Mentor:** Dr. Sahinur Laskar
**Team Members: ** 
1) Tanuja Bisht -> Data Preparation
2) Mayank Anand -> Model & System Architecture  

## 1. Introduction
This project uses Natural Language Processing (NLP) and
machine learning to classify news articles into categories.

## 2. Objective
The objective is to train and compare machine learning
models and predict the category of a news article.

## 3. Dataset
Source: Kaggle News Classification Dataset
https://www.kaggle.com/datasets/mmumairkhattak/news-classification-dataset-2026-nlp-and-tc

The dataset contains news text and category labels.
The actual dataset size and category names are reported
after running the program.

## 4. Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Natural Language Processing
- TF-IDF

## 5. Methodology
1. Load the dataset.
2. Remove missing and duplicate records.
3. Clean the news text.
4. Convert text into numerical features using TF-IDF.
5. Split the dataset into training and testing sets.
6. Train three machine learning models.
7. Evaluate and compare their performance.
8. Save the best model.
9. Predict categories for new news articles.

## 6. Machine Learning Models
- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Machine (Linear SVM)

## 7. Evaluation
The models are compared using accuracy, precision,
recall, weighted F1 score, and confusion matrices.

See the results folder for the actual experimental results.

## 8. How to Run
Install the required libraries:

    python -m pip install -r requirements.txt

Train and evaluate the models:

    python main.py

Predict a news category:

    python predict.py

## 9. Conclusion
This project demonstrates how NLP and machine learning
can be used to classify news articles automatically.
The best model is selected based on its weighted F1 score.

## 10. Future Scope
- Test more machine learning algorithms.
- Try advanced NLP models such as BERT.
- Build a web application for news classification.
- Improve performance using more diverse data.

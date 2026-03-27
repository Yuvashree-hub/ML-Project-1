# Personality Prediction from Text

## Overview
This project predicts a person's MBTI personality type from written text using Natural Language Processing and Machine Learning.

The model analyzes text posts and classifies them into personality types such as INTJ, ENFP, INTP, etc.

## Dataset
MBTI Personality Dataset

Download from:
https://www.kaggle.com/datasets/datasnaek/mbti-type

File used:
mbti_1.csv

Dataset columns:
- type → Personality type
- posts → Text posts written by the user

## Technologies Used
Python  
Pandas  
Scikit-learn  
TF-IDF Vectorization  
Naive Bayes Classifier

## Project Workflow

1. Load dataset
2. Preprocess text data
3. Convert text into numerical features using TF-IDF
4. Encode personality labels
5. Split dataset into training and testing
6. Train Naive Bayes classifier
7. Evaluate model performance
8. Predict personality from custom input text

## How to Run

1. Download the dataset
2. Place `mbti_1.csv` in the project folder
3. Run the Python script

```
python personality_prediction.py
```

4. Enter any text to predict personality type.

## Example

Input:
I enjoy solving complex problems and working alone on creative ideas.

Output:
Predicted Personality: INTJ


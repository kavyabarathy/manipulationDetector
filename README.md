# Manipulative Text Detector
A multi-class classification model that detects potential types of manipulation present in a user-inputted text trained on data from a Kaggle dataset.

## Overview
This project evaluates two different types of models (Random Forest and Logistic Regression) for the task of identifying specific manipulation types in conversational texts. The final product can classify a user-inputted text as a specific type of manipulation and provide a confidence score along with this prediction. 

## Dataset
Source: Kaggle (Psychological Manipulation Conversations dataset)
Format: .jsonl
Main features used: manipulation_type, messages, is_manipulation

## Project Pipeline
1. Import libraries
2. Uploading Dataset + Data Cleaning
3. Encoding
4. Training
5. Testing
6. Working Model + Interactive testing

## Conclusion
The Logistic Regression model performed better than the Random Forest model

## Limitations
1. The model is trained on synthetic data so it might struggle with real life examples
2. The model may also struggle with sarcasm or subtle manipulation

## Author
Kavya Barathy

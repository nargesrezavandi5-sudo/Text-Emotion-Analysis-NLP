# Text-Emotion-Analysis-NLP
This project is a machine learning and NLP-based system for classifying text into different emotion categories.   The goal is to detect the emotional state expressed in a sentence and assign it to the correct label.
## Project Description
The notebook `text_emition.ipynb` implements an emotion classification workflow using a dataset of text samples labeled with emotion categories.  
The pipeline includes data loading, preprocessing, label encoding, text cleaning, train-test splitting, model training, and evaluation.
Preprocessing Steps
The notebook performs the following preprocessing steps:

Loading the dataset with pandas
Checking class distribution using value_counts()
Extracting text and emotion columns
Encoding emotion labels using LabelEncoder
Cleaning text with regular expressions
Splitting the dataset into training and testing sets

# Text-Emotion-Analysis-NLP
This project is a machine learning and NLP-based system for classifying text into different emotion categories.   The goal is to detect the emotional state expressed in a sentence and assign it to the correct label.
## Project Description
The notebook `text_emition.ipynb` implements an emotion classification workflow using a dataset of text samples labeled with emotion categories.  
The pipeline includes data loading, preprocessing, label encoding, text cleaning, train-test splitting, model training, and evaluation.

## Dataset
The dataset is loaded from:
```python
df = pd.read_csv('text_emotion_assignment.csv')

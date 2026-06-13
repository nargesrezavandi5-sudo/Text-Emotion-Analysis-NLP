# Text-Emotion-Analysis-NLP
This project is a machine learning and NLP-based system for classifying text into different emotion categories.   The goal is to detect the emotional state expressed in a sentence and assign it to the correct label.
## Project Description
The notebook `text_emotion.ipynb` implements an emotion classification workflow using a dataset of text samples labeled with emotion categories.  
The pipeline includes data loading, preprocessing, label encoding, text cleaning, train-test splitting, model training, and evaluation.
## Preprocessing & Embedding Steps
The notebook performs the following steps to prepare text for the model:

*   **Loading:** Importing the dataset using `pandas`.
*   **Cleaning:** Removing special characters and noise using regular expressions.
*   **Encoding Labels:** Converting categorical emotion labels into numeric values using `LabelEncoder`.
*   **Tokenization & Embedding:** 
    *   Converting raw text into tokens suitable for model input.
    *   Mapping tokens to high-dimensional **embeddings** to capture semantic relationships and contextual nuances between words.
*   **Splitting:** Dividing the dataset into training and testing sets to evaluate model generalization.

Example:
```python
clean_text = [re.sub(r'[^\\w\\s]', '', x) for x in text]
# Embedding process typically follows here via Tokenizer/Transformer

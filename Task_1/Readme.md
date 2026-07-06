# News Topic Classifier Using BERT

## Project Overview
This project implements a News Topic Classification model using the BERT (Bidirectional Encoder Representations from Transformers) architecture. The model is fine-tuned on the AG News dataset to classify news headlines into four categories:

- World
- Sports
- Business
- Science/Technology

The project demonstrates the use of Hugging Face Transformers for natural language processing tasks, including tokenization, model fine-tuning, evaluation, and deployment.

---

## Objectives

- Load and preprocess the AG News dataset.
- Tokenize news headlines using BERT tokenizer.
- Fine-tune the pre-trained `bert-base-uncased` model.
- Evaluate model performance using Accuracy and F1-score.
- Save the trained model.
- Deploy the model using Streamlit.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- Scikit-learn
- Streamlit

---

## Dataset

AG News Dataset

Classes:
- World
- Sports
- Business
- Sci/Tech

---

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Tokenization
4. Train-Test Split
5. Fine-tune BERT
6. Evaluate Model
7. Save Model
8. Deploy using Streamlit

---

## Evaluation Metrics

- Accuracy
- Macro F1-Score
- Classification Report

---

## Results

The fine-tuned BERT model achieves high classification accuracy and effectively predicts the topic of unseen news headlines.

---

## Future Improvements

- Hyperparameter tuning
- Early stopping
- Deploy on Hugging Face Spaces
- Add confidence score for predictions

---

## Author

Nimra Ashraf

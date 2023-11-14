# Customer_complaints

## Overview

This project focuses on text classification of customer complaints using TF-IDF  to fit machine learning algorithm for predictions.

## Project Structure

The project is organized into the following key sections:

1. **Data Preprocessing:**
   - The dataset is mapped to required category.
   - Removed unwanted columns

2. **TF-IDF:**
   - finding the related content and important words and phrases in a larger text
   - Tokenize documents
   - Making TFIDF vectorizer to fit machine learning algorithm for predictions

3. **Machine Learning Models Training:**
   - Three multi-class classification models are implemented: Random Forest, Linear Support Vector Machine (Linear SVC), and Multinomial Naive Bayes.
   - The models are trained using the preprocessed and balanced dataset to classify customer complaints into relevant categories.
     
4. **Model Evaluation**
   - Confusion matrix to find thr accuracy precisoin and F1-Score

## Dependencies

Ensure you have the following libraries installed:

- pandas
- scikit-learn
- matplotlib
- imbalanced-learn
- spaCy

Install dependencies using:

```bash
pip install pandas scikit-learn imbalanced-learn spacy tqdm

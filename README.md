# Customer_complaints
# Text Classification and Oversampling

## Overview

This project focuses on text classification of customer complaints with a primary objective of addressing class imbalance through oversampling. The ultimate goal is to create a balanced dataset for training machine learning models and evaluate their performance using various classification algorithms.

## Project Structure

The project is organized into the following key sections:

1. **Data Preprocessing:**
   - The dataset is split into training and testing sets.
   - Data oversampling is implemented to address class imbalance, ensuring equal representation for each class.

2. **Text Cleaning:**
   - A dedicated function `text_Cleaning` is defined for preprocessing the text data.
   - Text cleaning techniques, including lowercase conversion, punctuation removal, and lemmatization using spaCy, are applied to enhance the quality of the text data.

3. **Resulting Dataset:**
   - The oversampled and preprocessed dataset is stored in a new DataFrame named `data_resampled`.

4. **Machine Learning Models Training:**
   - Three multi-class classification models are implemented: Random Forest, Linear Support Vector Machine (Linear SVC), and Multinomial Naive Bayes.
   - The models are trained using the preprocessed and balanced dataset to classify customer complaints into relevant categories.

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

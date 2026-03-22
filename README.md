# Python_PBL
Phase 1: Dataset Preparation & Preprocessing

🔹 Project Overview:

This project focuses on building a sentiment analysis system that classifies product reviews into Positive, Negative, and Neutral categories.
Phase 1 covers the initial steps of the machine learning pipeline, including dataset preparation and text preprocessing.

🔹 Objectives
Collect and prepare a dataset of product reviews
Convert ratings into sentiment labels
Clean and preprocess textual data
Prepare data for further machine learning tasks

🔹 Dataset
Source: Kaggle dataset (product reviews)
Data includes:
Review text
Rating (converted into sentiment)
✔️ Sentiment Conversion
Rating	   Sentiment
4–5	       Positive
 3	       Neutral
1–2	       Negative

🔹 Data Preprocessing Steps

The following preprocessing steps were applied:

1. Noise Removal
   Removed special characters, numbers, and punctuation
2. Lowercase Conversion
   Converted all text to lowercase for uniformity
3. Stopword Removal
   Removed common words like is, the, and
4. Lemmatization
   Reduced words to their base form
    Example: running → run

🔹 Technologies & Libraries Used
Python
Pandas
NumPy
NLTK
Regular Expressions (re)

🔹 Project Pipeline (Phase 1)
Dataset Collection
   ↓
Data Cleaning
   ↓
Sentiment Label Creation
   ↓
Text Preprocessing
   ↓
Clean Dataset Ready for ML

🔹 Output
Cleaned dataset with:
review (text)
sentiment (label)
Preprocessed text column (clean_review)

🔹 Repository Contents
Dataset file
Preprocessing code
Synopsis report
Output samples
Pipeline diagram

✔️ Conclusion

Phase 1 successfully prepares the dataset by cleaning and standardizing text data, making it suitable for machine learning models in the next phase.

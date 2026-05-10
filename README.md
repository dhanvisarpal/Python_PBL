# Sentiment Analysis of Product Reviews using Machine Learning

This repository contains a complete **Machine Learning and NLP-based Sentiment Analysis System** developed as a Project Based Learning (PBL) project. The project analyzes customer product reviews and classifies them into **Positive, Neutral, or Negative sentiments** using Natural Language Processing techniques and Machine Learning algorithms.

The project includes:

* Dataset preprocessing
* Exploratory Data Analysis (EDA)
* Text cleaning and NLP processing
* Feature extraction using TF-IDF
* Machine Learning model training
* Model evaluation and comparison

The system helps businesses and e-commerce platforms automatically understand customer opinions and improve decision-making based on review analysis.

---

# Problem Statement

Customers rely heavily on online product reviews before purchasing products. Manually analyzing thousands of reviews is difficult and time-consuming.

This project automates the process by:

* Extracting meaningful information from review text
* Converting text into numerical features
* Applying Machine Learning algorithms for sentiment prediction
* Evaluating model performance using multiple metrics

---

# PHASE:1 DATASET CREATION AND PREPROCESSING 

## Dataset Processing:
* Reading and handling CSV datasets
* Cleaning inconsistent and missing values
* Standardizing column names

## Sentiment Mapping:
Product ratings are converted into sentiment labels:
* **Positive → Rating ≥ 4**
* **Neutral → Rating = 3**
* **Negative → Rating < 3**

# Exploratory Data Analysis (EDA)
The project performs detailed data analysis using visualizations such as:
    * Rating Distribution Histogram
    * Like vs Dislike Count Plot
    * App Source Distribution Pie Chart
    * Sentiment Distribution Graphs
    * Confusion Matrix Heatmaps
EDA helps understand customer behavior and dataset trends.

# Text Preprocessing (NLP)
The review text is cleaned and transformed using several NLP techniques:
   * Lowercasing
   * Removing special characters and numbers
   * Removing punctuation
   * Tokenization
   * Stopword Removal using NLTK
   * Lemmatization using WordNetLemmatizer
   * Handling null and empty reviews
These preprocessing steps improve model accuracy and text quality.

# PHASE 2:MODEL TRAINING 

## Feature Engineering
The project creates meaningful numerical features from text data using:

## TF-IDF Vectorization
   * Converts review text into numerical vectors
   * Uses:
      * `max_features = 5000`
      * `ngram_range = (1,2)`
This captures:
    * Single words
    * Common phrases/bigrams

# Machine Learning Models Used
The project trains and compares multiple Machine Learning models:

## Logistic Regression
  * Optimized using:
    * `max_iter = 1000`

## K-Nearest Neighbors (KNN)
  * Configured with:
    * `n_neighbors = 5`
  * Cosine similarity metric

## Support Vector Machine (SVM)
   * Linear kernel
   * Probability estimation enabled
   * 
## Model Evaluation
The models are evaluated using:
* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC Curve
* AUC Score
The best-performing model is selected based on weighted F1-score and overall accuracy.

# Phase 3 – MODEL COMPARISION 
In Phase 3, different Machine Learning models were trained and compared to find the best model for sentiment classification of product reviews.

### Models Used
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)

### Comparison
 Model                      Performance                                            
  **Logistic Regression**    Fast and gave balanced results with good accuracy.     
  **KNN**                    Easy to implement but slower for large text datasets.  
  **SVM**                    Gave the highest accuracy and best prediction results. 

### Evaluation Metrics
The models were compared using:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Curve

### Final Result
Among all models, **SVM performed the best** for sentiment analysis because it handled TF-IDF text features more effectively and produced more accurate predictions. Logistic Regression also performed well, while KNN was comparatively slower and less efficient for text data.


# TECHNOLOGIES AND LIBRARIES USED 

## Programming Language
* Python

## Libraries
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Regular Expressions (re)
  
# Workflow
1. Import Libraries
2. Load Dataset
3. Clean Dataset
4. Perform Exploratory Data Analysis
5. Map Ratings to Sentiments
6. Preprocess Review Text
7. Apply TF-IDF Vectorization
8. Split Dataset into Train/Test Sets
9. Train Machine Learning Models
10. Evaluate and Compare Models
11. Predict Review Sentiments

# Applications
This project can be used in:
* E-commerce platforms
* Product review analysis
* Customer feedback systems
* Social media monitoring
* Business intelligence systems

# Platform Used
* Jupyter Notebook

# Future Improvements
* Deep Learning models (LSTM/BERT)
* Real-time sentiment prediction
* Web application integration
* Multi-language sentiment analysis
* Deployment using Flask/Streamlit
  
# Conclusion
This project demonstrates how Natural Language Processing and Machine Learning can be combined to automate sentiment analysis of product reviews. By analyzing customer opinions effectively, businesses can improve products, enhance customer satisfaction, and make data-driven decisions.

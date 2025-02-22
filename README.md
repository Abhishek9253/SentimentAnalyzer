
# Sentiment_Analyzer_Project for IBDM Movies Reviews

# Project Objective:
To develop a sentiment analysis system that automatically classifies the sentiment of movie reviews from IMDb into positive, negative, or neutral categories. This system will use machine learning algorithms and natural language processing techniques to understand and analyze textual data. The sentiment analysis will provide valuable insights into movie reviews by determining the overall public sentiment towards a movie.

# The project will be structured in the following phases:

## Data Collection & Preprocessing:

- Collect a dataset of IMDb movie reviews.
- Clean and preprocess the text data, including steps such as tokenization, stop-word removal, and stemming/lemmatization.
  
## Model Development:

- Utilize machine learning algorithms like Naive Bayes, Support Vector Machines (SVM), or Deep Learning models (like LSTMs) for sentiment classification.
- Apply NLP techniques such as TF-IDF, word embeddings (like Word2Vec or GloVe), or BERT-based models to extract meaningful features from the review text.

## Model Training & Evaluation:

- Split the data into training and testing sets.
- Train the model and evaluate its performance using metrics like accuracy, precision, recall, and F1-score.
- Fine-tune the model for better classification results.

## Flask Interface Development:

- Build a web interface using Flask to allow users to input movie reviews.
- Integrate the trained sentiment analysis model into the Flask app so that it can predict and display the sentiment of the input review in real-time.
- User Interaction & Visualization:

## Display the sentiment prediction on the interface (positive, negative).
- Optionally, visualize sentiment trends and distribution across various movies or genres.

## Key Technologies:
**Data Preprocessing**: Numpy, Pandas
**Machine Learning**: Scikit-learn
**NLP Techniques:** NLTK
**Flask Framework** for building the web interface.
**Data Visualization** : Matplotlib, Seaborn


# IMDB Movie review dataset: 
Link: https://github.com/Abhishek9253/SentimentAnalyzer/tree/main/Dataset

# Sentiment_Analyzer_Interface:
![Screenshot 2024-10-28 193925](https://github.com/user-attachments/assets/78f6aad4-cea0-4df7-b872-3b99f1fd8497)

# Installation

Use the package manager pip to install all dependencies.

```bash
pip install -r requirements.txt
```

# Outcome:
The final product will be a web-based sentiment analyzer that allows users to input movie reviews and receive an instant sentiment classification. This tool can be useful for moviegoers, filmmakers, or analysts interested in understanding public opinion towards a particular movie.

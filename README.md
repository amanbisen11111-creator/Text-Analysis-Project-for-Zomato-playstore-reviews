# Zomato Play Store Reviews Analysis

This project analyzes reviews of the Zomato app from the Google Play Store. The goal was to understand customer opinions by cleaning the raw reviews, running sentiment analysis, and identifying key discussion topics.

---

## Project Steps

### 1. Collecting Data
- Reviews were scraped from the Google Play Store using a scraper tool.
- The raw dataset was saved as an Excel file.

### 2. Cleaning the Data
- Removed missing values and unwanted characters.
- Converted all text to lowercase.
- Tokenized reviews and removed stopwords (using NLTK).
- Final cleaned text was stored in a new file for analysis.

### 3. Sentiment Analysis
- Used TextBlob to calculate sentiment polarity scores.
- Classified reviews as **Positive, Negative, or Neutral**.
- The output was stored in Excel along with the sentiment results.

### 4. Visualization
- Pie chart of sentiment distribution using Matplotlib.
- Bar charts showing the most frequent words in each topic.

### 5. Topic Modeling
- Applied TF-IDF and NMF (Non-Negative Matrix Factorization).
- Extracted 5 main topics from the reviews.
- Each topic shows the most relevant words that describe customer concerns.

---

## Files in the Repository
- `gba_playstore_comments.xlsx` → Raw reviews.  
- `aman_b.xlsx` → Preprocessed (cleaned) reviews.  
- `reviews_with_sentiment.xlsx` → Reviews with sentiment labels.  
- Python scripts for preprocessing, sentiment analysis, topic modeling, and visualization.  

---

## Tools and Libraries
- Python  
- Pandas  
- NLTK  
- TextBlob  
- Scikit-learn  
- Matplotlib / Seaborn  
- WordCloud  

---

## Sample Insights
- Most reviews are **positive**, highlighting fast delivery and discounts.  
- Negative reviews focus mainly on **late deliveries and customer support issues**.  
- Topics extracted include delivery speed, offers, app experience, and service quality.  

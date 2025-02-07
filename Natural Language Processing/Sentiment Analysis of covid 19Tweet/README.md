**Sentiment Analysis of COVID-19 Tweets**

### Project Overview
The COVID-19 pandemic has led to an unprecedented surge in information dissemination through social media platforms. This project aims to perform sentiment analysis on COVID-19-related tweets to understand public perceptions, sentiments, and emotions during the pandemic. Using various machine learning techniques, we classify the sentiments expressed in these tweets.

### Technologies Used
- Python
- Natural Language Processing (NLP) Libraries: NLTK, spaCy
- Machine Learning Libraries: scikit-learn, TensorFlow
- Data Visualization: Matplotlib, Seaborn
- Data Collection: Twitter API
- Google Colab

### Data Collection
- Gathered COVID-19-related tweets from Twitter's API using appropriate search queries and filters.
- Collected datasets covering different time periods (April - June 2020, April - June 2021, August - September 2020) to capture evolving sentiments over time.

### Methodology
1. **Data Preprocessing**: Cleaned the data by removing noise (special characters, URLs, emojis), tokenizing, and normalizing text.
2. **Data Labeling**: Manually labeled a subset of tweets into positive, negative, or neutral categories.
3. **Feature Extraction**: Used techniques like TF-IDF and word embeddings to convert text data into numerical feature vectors.
4. **Model Selection**: Experimented with multiple machine learning models including:
   - Naive Bayes
   - Support Vector Machines (SVM)
   - Logistic Regression
   - Random Forest
5. **Model Training and Evaluation**: Split the dataset into training and testing sets, trained models, and assessed performance using accuracy, precision, recall, and F1-score.

### Models
- **Naive Bayes (NB)**
- **Support Vector Machine (SVM)**
- **Logistic Regression (LR)**
- **Random Forest (RF)**

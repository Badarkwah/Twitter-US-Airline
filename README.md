
## Twitter US Airline Sentiment Analysis Project

### Overview 🌐

This project leverages **Twitter data** to analyze sentiments towards US airlines, aiming to classify tweets into positive 😊, neutral 😐, and negative 😠 sentiments.

### Problem Statement 🚀

With Twitter's vast user base, sentiment analysis becomes crucial for monitoring customer sentiments. This project builds a machine learning model to classify the sentiment of tweets related to US airlines.

### Data Dictionary 📊

| Column Name                   | Description                                   |
| ----------------------------- | --------------------------------------------- |
| `tweet_id`                    | Unique identifier for tweets                  |
| `airline_sentiment`           | Sentiment of the tweet (positive/negative/neutral) |
| `airline_sentiment_confidence`| Confidence level of the sentiment             |
| `negativereason`              | Reason for negative sentiment                 |
| `text`                        | Text content of the tweet                     |
| ...                           | ...                                           |

### Methodology 🛠️

1. **Data Preprocessing**: Cleaning text data, handling missing values.
2. **Exploratory Data Analysis (EDA)**: Analyzing tweet sentiments.
3. **Feature Engineering**: Using TF-IDF for text vectorization.
4. **Model Development**: Implementing Random Forest Classifier.
5. **Model Evaluation**: Using accuracy, confusion matrix.

### Key Insights 🔑

- Distribution of sentiments across airlines.
- Common reasons for negative sentiments were identified.
- Random Forest model showed robust performance.

### Conclusion 📝

This project highlights the importance of sentiment analysis in social media marketing, offering a practical tool for businesses to monitor customer sentiments on Twitter.


# 📊 ChatGPT Review Analysis

## Project Overview

This project analyzes customer reviews of ChatGPT to understand user
satisfaction, sentiment, and the specific features or aspects that users
frequently praise or criticize.

The project uses Exploratory Data Analysis (EDA), Natural Language
Processing (NLP), sentiment analysis, keyword extraction, phrase
analysis, and data visualization.

## Objectives

- Analyze the distribution of user ratings.
- Understand overall customer sentiment.
- Calculate sentiment polarity and subjectivity.
- Compare textual sentiment with numerical ratings.
- Identify frequently mentioned positive features.
- Identify common complaints and critical feedback.
- Analyze review trends over time.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- WordCloud
- Google Colab

## Analysis Performed

### Data Preparation

- Loaded and inspected the dataset.
- Standardized column names.
- Handled missing values.
- Converted ratings to numeric format.
- Converted review dates to datetime.
- Checked duplicate records.
- Cleaned review text.

### Exploratory Data Analysis

- Rating distribution
- Rating percentage
- Review length distribution
- Review length by rating
- Monthly review volume
- Average rating over time
- Rating distribution by month

### Sentiment Analysis

TextBlob was used to calculate:

- Sentiment polarity
- Sentiment subjectivity

Reviews were classified into:

- Positive
- Neutral
- Negative

### Text Analysis

- Most common words
- Word frequency
- Word cloud
- Positive keywords
- Positive phrases
- Negative keywords
- Critical feedback categories

## Key Business Questions

1. What is the overall sentiment of ChatGPT users?
2. Are textual sentiments consistent with numerical ratings?
3. What features do users appreciate most?
4. What problems do users mention most frequently?
5. How does user feedback change over time?

## Project Workflow

Raw Data  
↓  
Data Cleaning  
↓  
Feature Engineering  
↓  
EDA  
↓  
Text Preprocessing  
↓  
Sentiment Analysis  
↓  
Keyword Extraction  
↓  
Positive & Negative Feedback Analysis  
↓  
Insights & Recommendations

## How to Run

1. Open the notebook in Google Colab.
2. Upload the `chatgpt_reviews.csv` dataset when prompted.
3. Install the required Python libraries.
4. Run the notebook cells from top to bottom.

## Author

**Ravikiran Y**

GitHub: https://github.com/ravikiran966

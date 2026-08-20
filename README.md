# CodeAlpha Sentiment Analysis

## CodeAlpha Data Analytics Internship – Task 4

This project performs sentiment analysis and emotion analysis on Amazon customer reviews using Natural Language Processing (NLP) techniques.

## Project Objective

The objective of this project is to analyze customer reviews, classify them into positive, neutral, and negative sentiments, identify specific emotions, and generate meaningful insights that can support marketing and product-development decisions.

## Dataset

The dataset contains Amazon customer reviews with sentiment labels, review scores, and review text.

### Dataset Information

- Original Rows: 10,827
- Cleaned Rows: 9,829
- Sentiment Classes: Positive, Neutral, Negative
- Review Score: 1–5 stars

## Data Cleaning

The following preprocessing steps were performed:

- Missing values were handled
- Duplicate records were removed
- Review text was cleaned
- Review length was calculated
- Dataset consistency was checked
- Cleaned data was used for further analysis

## Sentiment Distribution

The cleaned dataset contains:

- Positive: 4,642 reviews
- Neutral: 4,035 reviews
- Negative: 1,152 reviews

## NLP Emotion Analysis

NRC Emotion Lexicon was used to identify emotions from customer reviews.

The emotions analyzed were:

- Joy
- Anger
- Sadness
- Fear
- Surprise
- Disgust

## Top Words

Frequently occurring words were analyzed separately for:

- Positive reviews
- Neutral reviews
- Negative reviews

This helped identify common customer concerns and positive product-related terms.

## Visualizations

The project includes:

1. Sentiment Distribution
2. Review Score Distribution
3. Sentiment vs Review Score
4. Review Length by Sentiment
5. Average Review Length by Sentiment
6. Emotion Analysis
7. Top Words Analysis
8. Final Sentiment Analysis Dashboard

## Key Insights

1. Positive sentiment represents the largest share of reviews.
2. Negative sentiment represents the smallest share of reviews.
3. Positive reviews have the highest average review score.
4. Negative reviews tend to contain longer reviews.
5. Five-star reviews have the largest number of positive reviews.
6. Joy is the most frequently detected emotion.
7. Negative reviews contain stronger indicators of anger and sadness.
8. Product performance, charging, working issues, and durability appear frequently in customer reviews.

## Business Recommendations

### 1. Improve Product Reliability

Frequent negative mentions related to products stopping, breaking, or not working suggest that reliability should be monitored.

### 2. Address Customer Complaints

Negative reviews can be analyzed to identify recurring product problems and prioritize improvements.

### 3. Leverage Positive Feedback

Frequently occurring positive terms can help identify product features customers value.

### 4. Monitor Emotional Patterns

Emotion analysis can help businesses identify frustration, dissatisfaction, and positive customer experiences.

### 5. Improve Product Development

Customer feedback can be converted into actionable insights for future product improvements.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- NRC Emotion Lexicon
- Scikit-learn
- WordCloud
- Google Colab

## Project Structure


CodeAlpha_SentimentAnalysis/
│
├── README.md
├── CodeAlpha_Task4_Sentiment_Analysis.ipynb
├── requirements.txt

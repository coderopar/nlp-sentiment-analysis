Twitter Sentiment Analysis: Apple vs Google
📌 Project Overview

This project analyzes Twitter posts related to Apple and Google to determine the sentiment expressed in each tweet — Positive, Negative, or Neutral.
It leverages Natural Language Processing (NLP) and Machine Learning to provide businesses with real-time insights into brand perception.

🎯 Business Problem

In today’s fast-paced digital world, customers share their opinions instantly on platforms like Twitter.
Manually reviewing thousands of tweets is time-consuming and impractical.
This project automates sentiment detection, enabling companies to:

Monitor brand reputation

Identify customer pain points early

React quickly to negative sentiment trends

Track marketing campaign performance

👥 Stakeholders

Marketing Teams – Measure campaign impact and sentiment shifts

Product Managers – Detect product issues and opportunities for improvement

Customer Support – Address negative feedback promptly

Executives – Guide brand strategy using real-time customer insights

📂 Data Sources

Publicly available tweets mentioning Apple and Google

Collected using the Twitter API

Pre-labeled for sentiment analysis (Positive, Neutral, Negative)

🛠 Methodology

Data Collection – Gather tweets using keywords, hashtags, and brand mentions

Data Cleaning – Remove URLs, punctuation, stopwords, and special characters

Text Processing – Tokenization, lowercasing, and lemmatization

Model Training – Train a sentiment classification model using NLP features

Visualization – Display sentiment distribution and trends over time

📊 Sentiment Distribution

Below is an example distribution of sentiment for Apple and Google tweets:

📊 Key Insights

Positive sentiment dominated discussions for both brands

Negative spikes were linked to product issues or controversial announcements

Neutral sentiment formed a steady baseline

💡 Business Value

Improves responsiveness to customer concerns

Supports data-driven marketing strategies

Enhances competitive analysis between Apple and Google

🚀 How to Run the Project

Clone this repository:

git clone <repo_url>
cd sentiment_analysis_project


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook:

jupyter notebook sentiment_analysis.ipynb
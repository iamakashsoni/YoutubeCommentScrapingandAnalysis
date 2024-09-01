# 📊 YouTube Comment Sentiment Analysis

## Introduction

Welcome to the **YouTube Comment Sentiment Analysis** project, a real-time sentiment analysis website for YouTube comments. This website employs natural language processing techniques to analyze comments and determine their sentiment, classifying them into positive, negative, or neutral categories. The project aims to provide valuable insights to content creators, marketers, and researchers by understanding the sentiment of their audience on YouTube.

## Features

- **Real-time Sentiment Analysis**: The website analyzes YouTube comments in real-time and displays the results.
- **Sentiment Visualization**: The sentiment analysis results are presented in the form of interactive pie charts for easy understanding.
- **User-friendly Interface**: The website offers a simple and intuitive interface for users to enter a YouTube video URL and view the sentiment analysis.

## Tech Stack

- **Backend**: Flask (Python web framework)
- **Web Scraping**: Selenium (with ChromeDriver)
- **Natural Language Processing**: NLTK (Natural Language Toolkit)
- **Data Visualization**: Pie charts

## How It Works

1. **User Interaction**: Users enter a YouTube video URL on the website.
2. **Web Scraping**: The website uses Selenium and ChromeDriver to scrape the comments from the specified YouTube video.
3. **Sentiment Analysis**: The scraped comments are analyzed using NLTK's sentiment analysis tools, classifying them as positive, negative, or neutral.
4. **Data Visualization**: The sentiment analysis results are displayed as interactive pie charts on the website.

## Purpose

The **YouTube Comment Sentiment Analysis** project aims to provide a valuable tool for content creators, marketers, and researchers to gain insights into the sentiment of their audience on YouTube. By understanding the sentiment of comments, users can make data-driven decisions to improve their content and engage with their audience more effectively.

## Future Enhancements

- **Sentiment Analysis Accuracy**: Explore advanced NLP techniques and machine learning algorithms to improve the accuracy of sentiment classification.
- **Multilingual Support**: Extend the sentiment analysis capabilities to support multiple languages.
- **Sentiment Trend Analysis**: Provide historical sentiment trend analysis to identify changes in audience sentiment over time.
- **Sentiment-based Recommendations**: Offer personalized recommendations based on the sentiment of comments, such as suggesting similar content or addressing common concerns.
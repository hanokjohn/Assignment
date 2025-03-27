Sentiment Analysis of Social Media Reviews

Overview

This project performs sentiment analysis on social media reviews using Azure's sentiment analysis tools. The data is loaded from a database, analyzed, and then saved back with sentiment labels. Additional analysis includes word and phrase frequency analysis and sentiment distribution by various metrics.

Features

Connects to a database to fetch social media reviews.

Uses Azure Cognitive Services for sentiment analysis to classify reviews as Positive, Neutral, or Negative.

Stores sentiment analysis results back into the database.

Performs word and phrase frequency analysis to identify common words and phrases.

Logs errors and execution flow for better debugging.

Technologies Used

Python (Pandas, SQLAlchemy, Scikit-learn, Logging)

Azure Cognitive Services for Sentiment Analysis

Azure SQL Database or Local Database

ODBC Driver for SQL Server

Sklearn CountVectorizer

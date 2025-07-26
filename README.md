Amazon  Product Review Sentiment Analysis
This project analyzes customer reviews of Amazon Alexa to determine the overall sentiment—whether users feel positively, negatively, or neutral about the product. It uses Python, pandas, and VADER (Valence Aware Dictionary and sEntiment Reasoner) from the NLTK library to calculate sentiment scores and visualize the results.

Table of Contents
Overview

Installation

Dataset

Usage

Output

Visualization

Dependencies

 Overview
The notebook performs the following steps:

Loads a tab-separated file (amazon.txt) of customer reviews

Uses VADER from NLTK to compute sentiment polarity scores (Positive, Negative, Neutral)

Aggregates the results to determine the overall product sentiment

Visualizes the review ratings using a pie chart



Run the Python script or Jupyter notebook.

It will:

Load and preview the dataset

Analyze sentiment using VADER

Count the number of positive, negative, and neutral reviews

Determine the overall sentiment

Display a pie chart of ratings

Example sentiment output:

text
Copy
Edit
Overall Sentiment: Positive
📊 Visualization
The notebook generates a pie chart showing the distribution of star ratings (1–5):


 Dependencies
pandas

matplotlib

seaborn

nltk


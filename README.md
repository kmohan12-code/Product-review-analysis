Amazon Product Review Sentiment Analysis
Overview
This project analyzes customer reviews of Amazon Alexa to determine the overall sentiment — whether users feel positive, negative, or neutral about the product.
It uses Python, pandas, and VADER (Valence Aware Dictionary and sEntiment Reasoner) from the NLTK library to calculate sentiment scores and visualize the results.

Features
Loads customer reviews from a tab-separated file (amazon.txt)

Uses VADER to compute sentiment polarity scores (Positive, Negative, Neutral)

Aggregates sentiment scores to find overall product sentiment

Visualizes star rating distribution using a pie chart

How It Works
Load and preview the dataset containing customer reviews.

Use VADER to analyze sentiment polarity of each review.

Count how many reviews are positive, negative, or neutral.

Determine the overall sentiment of the product based on review sentiments.

Generate a pie chart visualizing the distribution of star ratings (1 to 5 stars).

Example Output
yaml
Copy
Edit
Overall Sentiment: Positive
Visualization
A pie chart displays the proportion of each star rating to give a clear visual overview of customer feedback.

Dependencies
pandas — data handling

matplotlib — plotting charts

seaborn — enhanced visualization

nltk — natural language processing, including VADER sentiment analysis

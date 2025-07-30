Amazon Echo Review Sentiment Analysis
This project analyzes customer reviews for the Amazon Echo smart speaker. Using sentiment analysis with NLTK's VADER, the script determines the overall sentiment of the reviews and visualizes the distribution of product ratings.

Dataset
The dataset is a tab-separated file named Amazon.txt, which contains the following columns:

rating: Integer values from 1 to 5 indicating the user rating for the Amazon Echo.

date: The date when the review was posted.

variation: Describes the specific product variation (e.g., color, model, or fabric type).

verified_reviews: The text content of the customer’s review.

feedback: A value of 1 (positive feedback) or 0 (negative feedback), indicating if the customer had a favorable or unfavorable review.

Sample data:

rating	date	variation	verified_reviews	feedback
5	31-Jul-18	Charcoal Fabric	Love my Echo!	1
4	31-Jul-18	Walnut Finish	"Sometimes while playing a game, you can answer a question correctly but Alexa says you got it wrong."	1
5	31-Jul-18	Charcoal Fabric	"I have had a lot of fun with this thing. My 4 yr old learns about dinosaurs, and I control the lights."	1
5	30-Jul-18	Heather Gray Fabric	"Love it! I’ve listened to songs I haven’t heard since childhood!"	1

 Requirements
Before running the script, install the following libraries:

pip install pandas matplotlib seaborn nltk
Additionally, download the VADER lexicon for NLTK:


Load Data:

Reads the dataset of Amazon Echo reviews.

Visualize Ratings:

Creates a pie chart showing the proportion of ratings (1 to 5) given by customers.

Sentiment Analysis:

Uses NLTK's SentimentIntensityAnalyzer to compute the following sentiment scores:

Positive sentiment score

Negative sentiment score

Neutral sentiment score

Aggregates the sentiment scores and classifies the overall sentiment (Positive, Negative, or Neutral).

Output:

Displays whether the overall sentiment is Positive, Negative, or Neutral.

📊 Sample Output
Pie chart of ratings for the Amazon Echo:

(insert screenshot here if needed)

Console output:

mathematica
Copy
Edit
Positive
 File Structure
bash
Copy
Edit
project-directory
│
├── Amazon.txt         
├── sentiment_analysis.py  
└── README.md           
 To Run



# Amazon Echo Review Sentiment Analysis

This repository contains a script for analyzing customer reviews of the **Amazon Echo** using sentiment analysis. It uses the **NLTK VADER Sentiment Analyzer** to classify review sentiments as Positive, Negative, or Neutral. The results are visualized using **Matplotlib** and **Seaborn**.



The dataset is a **tab-separated file** named `Amazon.txt`, which includes the following columns:

* **`rating`**: User rating (1 to 5) for the Amazon Echo.
* **`date`**: Date of review submission.
* **`variation`**: The specific variation (e.g., color, fabric).
* **`verified_reviews`**: Customer’s review text.
* **`feedback`**: 1 (positive feedback) or 0 (negative feedback).

##  Requirements

Install the required libraries using **pip**:

```bash
pip install pandas matplotlib seaborn nltk
```

Download the NLTK VADER lexicon (run once):

```python
import nltk
nltk.download('vader_lexicon')
```

## How the Script Works

1. **Load Data**: The script loads reviews from the `Amazon.txt` file.
2. **Visualize Ratings**: A pie chart shows the distribution of ratings (1–5).
3. **Sentiment Analysis**: Reviews are analyzed using **NLTK's VADER Sentiment Analyzer** to calculate positive, negative, and neutral sentiment scores.
4. **Classify Overall Sentiment**: The script calculates the overall sentiment (Positive, Negative, or Neutral) based on aggregated sentiment scores.

##  Results

### Pie Chart of Ratings

The script generates a pie chart to show how many users gave each rating (1–5) for the Amazon Echo.

### Example Output

**Overall Sentiment:**

```
Positive
```

##  File Structure

```
 project-directory
│
├── Amazon.txt             
├── sentiment_analysis.py  
└── README.md              
```

2. Navigate to the project directory:

   ```bash
   cd amazon-echo-sentiment-analysis
   ```

3. Run the script:

   ```bash
   python sentiment_analysis.py
   ```

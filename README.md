# Stock News Sentiment Analyzer

This project analyzes the sentiment of real-time news articles related to a given stock or company. It uses NewsAPI to fetch news headlines and TextBlob for sentiment analysis. Results can be displayed either in the console or through a Streamlit web interface.

## Features

- Fetches latest news headlines for a given stock or company
- Analyzes sentiment using natural language processing (TextBlob)
- Displays headline-wise sentiment scores
- Calculates and reports the average sentiment score
- Optionally runs with a Streamlit GUI

## Technologies Used

- Python
- requests
- pandas
- textblob
- streamlit (optional)

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   
Install dependencies:
pip install -r requirements.txt

Or manually 
pip install yfinance requests textblob pandas streamlit

Replace the API key in the script:
apiKey = 'your_newsapi_key'



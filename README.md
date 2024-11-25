Stock Movement Analysis on Reddit

Overview
This project predicts stock movements by analyzing sentiment data scraped from Reddit. It extracts stock mentions, performs sentiment analysis, and trains a machine learning model to forecast stock trends.

Features
- Reddit scraping for stock-related discussions.
- Sentiment analysis using the VADER model.
- Machine learning model for stock trend prediction.

Prerequisites
- Python 3.8+
- A Reddit developer account for API credentials.


Install required Python libraries:
pip install praw pandas scikit-learn nltk matplotlib


Configure your Reddit API credentials:

- Go to Reddit App Preferences.
- Create a new script app and note the client_id, client_secret, and user_agent.
- Update the script with these credentials.
  
Download NLTK resources:
python -c "import nltk; nltk.download('vader_lexicon')"

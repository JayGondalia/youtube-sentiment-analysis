# YouTube Comments Sentiment Analysis

This repository contains a Jupyter notebook that performs sentiment analysis on YouTube comments. The process involves fetching comments from a YouTube video, preprocessing the text data, performing sentiment analysis, and training machine learning models to classify the sentiments.

## Requirements

To run this notebook, you will need the following:

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Google API key with YouTube Data API access

## Installation

1. clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/youtube-comments-sentiment-analysis.git
cd youtube-comments-sentiment-analysis

2. Install the required packages:
pip install numpy pandas matplotlib google-api-python-client nltk scikit-learn spacy

3. Download NLTK and SpaCy models:
python -m nltk.downloader vader_lexicon stopwords wordnet
python -m spacy download en_core_web_md


## Configuration
Replace the placeholder API key and video ID with your own:
api_key = 'YOUR_API_KEY'
video_id = 'YOUR_VIDEO_ID'

## Additional Notes
Ensure you have enabled the YouTube Data API in your Google Cloud project and have a valid API key.
This notebook is designed to be run in a Jupyter Notebook environment.
Feel free to customize the preprocessing steps and model training parameters as needed.
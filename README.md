# Twitter-API-Sentiment-Analysis

This repository provides tools for performing sentiment analysis on tweets using the Twitter API. It uses the RoBERTa model fine-tuned for sentiment classification to analyze tweets fetched from specific users.

## Features
- Fetch tweets using Twitter API
- Sentiment analysis using `twitter-roberta-base-sentiment` model
- Streamlit dashboard for visualization

## Prerequisites
- Python 3.6 or above
- Twitter Developer Account and API keys

## Installation

Clone the repository:

```
git clone https://github.com/furkandrms/Twitter-API-Sentiment-Analysis.git
cd Twitter-API-Sentiment-Analysis
```

Install the required packages:

```
pip install -r requirements.txt
```

## Usage

1. Enter your API keys in the configuration file.
2. Run the main script to fetch tweets and perform sentiment analysis:
   ```
   python main.py
   ```
3. To view the dashboard, run:
   ```
   streamlit run streamlitDashboard.py
   ```

## Contributing
Feel free to fork the repository, make changes, and submit pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

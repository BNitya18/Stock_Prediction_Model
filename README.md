# AI Financial Advisor with Stock Prediction

This is an interactive web-based application that combines **stock prediction** using machine learning (Random Forest Classifier) and **sentiment analysis** based on recent financial news to predict stock movements. The app fetches historical stock data, analyzes recent news sentiment, and makes predictions about stock price movements, providing valuable insights for traders and investors.

## Features

- Fetch stock data for a specified ticker symbol (e.g., AAPL, TSLA).
- Visualize historical stock trends (1-year data).
- Perform sentiment analysis on recent financial news related to the stock.
- Train a Random Forest model to predict stock price movement (up or down).
- Combine sentiment analysis with machine learning predictions for a more accurate forecast.
- Display prediction results based on historical data and sentiment.

## Requirements

Before running this app, make sure you have the following Python libraries installed:

- `yfinance` - To fetch stock data from Yahoo Finance.
- `pandas` - For data manipulation.
- `matplotlib` - To plot the stock price trend.
- `streamlit` - For creating the web interface.
- `sklearn` - For machine learning model and data scaling.
- `newspaper3k` - To fetch and parse financial news articles.
- `textblob` - For sentiment analysis.
- `vaderSentiment` - For another sentiment analysis method.

### Install dependencies

You can install the necessary libraries using `pip`:

```bash
pip install yfinance pandas matplotlib streamlit scikit-learn newspaper3k textblob vaderSentiment
```
### How to Use


Clone this repository to your local machine:

```bash

git clone https://BNitya18/Stock_Prediction_Model.git
cd Stock_Prediction_Model
```
Install the required dependencies (if not done already):

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash

streamlit run app.py
```

` Open your browser and navigate to http://localhost:8501 to view the app.

# Usage Steps

Step 1: Enter a stock ticker symbol (e.g., AAPL, TSLA) in the text input box.

Step 2: The app will fetch the stock data and financial news related to the ticker symbol.

Step 3: The app will display the sentiment score for the financial news.

Step 4: The historical stock trends for the ticker will be visualized.

Step 5: The model will be trained on the stock data, and the accuracy will be displayed.

Step 6: Finally, the app will predict the stock's movement (up or down) based on the historical data and sentiment analysis.

# Model Details



The sentiment analysis is performed using two methods:

- TextBlob: A general-purpose sentiment analysis tool based on polarity.

- VADER: A sentiment analysis tool specifically designed for social media and short texts.

- Machine Learning Model:

- Random Forest Classifier: This machine learning model is trained on historical stock data and attempts to predict the stock's direction (up or down) based on features like open, high, low, close prices, and volume.

## Contributing

We welcome contributions to enhance the functionality of the app. Feel free to fork this project and submit pull requests.


To contribute, please follow these steps:


Fork this repository.

Create a new branch (git checkout -b feature-branch).

Make your changes.

Commit your changes (git commit -am 'Added new feature').

Push to the branch (git push origin feature-branch).

Create a new Pull Request.

# License

This project is open-source and available under the MIT License.


# Acknowledgments

We would like to express our gratitude to the following:


- yfinance: For providing easy access to stock data, which allows the app to fetch historical market information.
- newspaper3k: For enabling the extraction and parsing of financial news articles from various sources.
- TextBlob: For providing a simple and efficient way to perform sentiment analysis on the fetched news articles.
- VADER Sentiment: For offering a specialized sentiment analysis tool tailored to short texts, such as social media posts and financial news.
- Scikit-learn: For providing the machine learning tools and algorithms used in the project, including Random Forest Classifier for stock movement prediction.
- Streamlit: For allowing the creation of the interactive web application with minimal effort, making the user interface simple and engaging.
- Additionally, we thank the broader open-source community for providing these powerful libraries and tools, enabling the development of this app.

# Project Description

The AI Financial Advisor with Stock Prediction is an interactive web-based application designed to assist investors and traders in making more informed decisions. It combines machine learning and sentiment analysis to predict stock price movements. The app fetches historical stock data and recent financial news, analyzes the sentiment of the news, and uses a Random Forest model to predict whether a stock’s price will go up or down. The prediction is enhanced by the sentiment score of the related news, providing a more comprehensive forecast.

# Who It's For

This app is tailored for:

Retail Investors: Individual investors looking for insights into stock trends and market sentiment.

Traders: Those who need quick and actionable predictions to guide day trading or short-term investments.

Financial Analysts: Professionals interested in combining machine learning with sentiment analysis for market predictions.

Tech Enthusiasts: Anyone curious about AI-driven financial applications and stock market analysi

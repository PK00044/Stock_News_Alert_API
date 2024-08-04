# Stock News Alert API

This project is a Stock News Alert system that fetches stock data using AlphaVantage, retrieves related news using NewsAPI.org, and sends alerts via SMS using Twilio.

## Features

- Fetch stock data for a specific company using the AlphaVantage API.
- Retrieve the latest news articles related to the company using the NewsAPI.org API.
- Send an SMS alert with the stock status and relevant news using Twilio.

## Prerequisites

Before running the application, ensure you have the following:

- **Python 3.x** installed
- **Twilio Account**: [Sign up here](https://www.twilio.com/try-twilio) for a free account and obtain your account SID, auth token, and a Twilio phone number.
- **AlphaVantage API Key**: [Get an API key](https://www.alphavantage.co/support/#api-key) to access stock data.
- **NewsAPI.org API Key**: [Sign up for an API key](https://newsapi.org/register) to retrieve news articles.

## The message will be for example
TSLA: 🔺1%
Headline: Klage gegen Tesla: Aktionäre sehen Bevorzugung von xAI gegenüber Tesla. 
Brief: Tesla-Aktionäre sehen eine Verschiebung von "Talenten und Ressourcen" in Richtung Elon Musks KI-Unternehmen xAI und klagen – auch gegen den Tesla-Vorstand.

## Configuration
You can customize the script by modifying the following parameters:

Stock Symbol: Change the stock symbol in the script to monitor a different company.
Alert Threshold: Set the price change threshold to trigger an alert.
Number of News Articles: Configure how many news articles to include in the alert.

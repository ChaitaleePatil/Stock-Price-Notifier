# Stock-Price-Notifier

This project is a Python script that monitors stock prices and sends relevant news updates via WhatsApp if there is a significant price change. It's particularly useful for staying updated on important market movements.

## Output
![2](https://github.com/user-attachments/assets/a46b5266-e123-4c65-b401-1962a1f5c498)


## Features
- Retrieves daily stock price data from Alpha Vantage.
- Checks for significant changes in stock prices (e.g., >5%).
- Fetches the latest news related to the company if there is a significant price change.
- Sends the news headlines and descriptions via WhatsApp using Twilio.

## Prerequisites
- Python 3.x
- Requests library (`pip install requests`)
- Twilio library (`pip install twilio`)
- Alpha Vantage API key
- News API key
- Twilio account with a verified WhatsApp number

## How to Use
1. Clone this repository.
2. Replace `YOUR_STOCK_API_KEY`, `YOUR_NEWS_API_KEY`, `YOUR_TWILIO_SID`, and `YOUR_TWILIO_AUTH_TOKEN` with your own credentials.
3. Replace `recipient_whatsapp_number` with your verified WhatsApp number.
4. Run the script using `main.py`.

## Contributing
Feel free to open issues or submit pull requests if you'd like to contribute to this project.

## Contact
For any questions, feel free to reach out via GitHub.

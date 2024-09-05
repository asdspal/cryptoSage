# CryptoSage: AI-Powered Cryptocurrency Assistant

## Overview

CryptoSage is an advanced AI-driven cryptocurrency bot designed to empower traders, investors, and crypto enthusiasts with comprehensive market insights, real-time analysis, and actionable recommendations. Developed for the Capx AI Agent Hackfest, CryptoSage combines cutting-edge AI algorithms with extensive market data to provide users with a competitive edge in the volatile world of cryptocurrency trading. It also introduces a groundbreaking crypto credit scoring system, bridging the gap between traditional finance and the crypto ecosystem.

## Key Features

- 📊 Advanced Token Analysis
- 💡 AI-Driven Buy/Sell Recommendations
- 📱 Multi-Platform Accessibility (Telegram, Web Interface)
- 🔍 Comprehensive Coin Tracking
- 📈 Sentiment Analysis
- 💼 Portfolio Management
- 🚀 Customizable Alerts
- 🧠 AI-Powered Market Insights
- 🔒 Enhanced Security and Privacy
- 💳 Crypto Credit Scoring

## Getting Started

### Prerequisites

- Python 3.8+
- Telegram Bot API Token
- Access to cryptocurrency market data APIs (e.g., CoinGecko, Binance)
- Access to DeFi protocols for credit scoring integration

### Installation

1. Clone the repository:
git clone https://github.com/asdspal/cryptosage.git


2. Install required dependencies:

pip install -r requirements.txt


3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your API keys and tokens:
     ```

 TELEGRAM_BOT_TOKEN=your_telegram_bot_token
 COINGECKO_API_KEY=your_coingecko_api_key
 DEFI_PROTOCOL_API_KEY=your_defi_protocol_api_key
 


4. Run the bot:

python main.py


## Usage

1. Start a chat with the CryptoSage bot on Telegram
2. Use commands like `/analyze BTC` to get insights on specific cryptocurrencies
3. Set up alerts using `/alert BTC above 50000`
4. Check your portfolio with `/portfolio`
5. Get your crypto credit score with `/creditscore`

For a full list of commands, type `/help` in the Telegram chat.

## Crypto Credit Scoring

CryptoSage now offers a unique credit scoring feature that assesses your crypto portfolio and trading history. This score can be used to access exclusive rates on partnered DeFi platforms. To get your crypto credit score:

1. Link your wallets using `/linkwallet`
2. Request your credit score with `/creditscore`
3. View potential loan offers with `/loanoffers`

## Contributing

We welcome contributions to CryptoSage! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Capx AI for hosting the AI Agent Hackfest
- [List any other libraries or resources you've used]

## Contact

For any queries or support, please join our [Telegram community](https://t.me/cryptosage_community) or follow us on [Twitter](https://twitter.com/cryptosage_ai).



# Alpaca Dashboard

A web dashboard for monitoring your Alpaca trading account in real-time.

![Dashboard Preview](screenshot.png)

## Features

- 📱 Mobile-first responsive design
- 🎨 Modern dark theme with smooth animations
- 🔒 Secure - credentials never leave your browser
- ⚡ Auto-refreshes every 30 seconds
- 📊 Real-time portfolio metrics (equity, cash, buying power, daily P&L)
- 📈 Live position tracking with profit/loss

## Quick Start

### Live Demo
Access the dashboard at: [https://justinoros.github.io/alpaca-dashboard](https://justinoros.github.io/alpaca-dashboard)

### Local Setup
1. Clone the repository
2. Open `index.html` in your browser
3. Enter your Alpaca API credentials
4. Select Paper or Live trading
5. Click **GO!**

## Getting API Credentials

1. Log in to [app.alpaca.markets](https://app.alpaca.markets)
2. Navigate to Paper Trading or Live Trading
3. Go to "Your API Keys"
4. Copy your API Key and Secret Key

⚠️ **Never share or commit your API credentials**

## What's Displayed

**Account Summary:**
- Portfolio Value
- Cash Balance
- Buying Power
- Today's P&L ($ and %)

**Positions:**
- Symbol, Quantity, Avg Cost
- Current Price, Market Value
- Unrealized P&L ($ and %)

## Technical Details

- Pure HTML/CSS/JavaScript (no frameworks)
- Paper API: `https://paper-api.alpaca.markets`
- Live API: `https://api.alpaca.markets`
- Works on all modern browsers

## Security

- Credentials stored in memory only
- No server-side components
- No third-party data sharing
- Read-only dashboard

## License

MIT License

## Disclaimer

For informational purposes only. Not financial advice. Developer not affiliated with Alpaca Markets.

---

**Built for traders who want a simple, clean portfolio view.**

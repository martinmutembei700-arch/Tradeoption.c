# Martin Trade — Real-Time Paper Trading

This version uses Finnhub for stock quotes. It remains paper trading: the $10,000 is virtual and no real orders are sent.

## Run locally
1. Install Node.js 18+.
2. Open a terminal in this folder.
3. Run: `npm install express`
4. Set your Finnhub API key:
   - Windows PowerShell: `$env:FINNHUB_API_KEY="YOUR_KEY"`
   - macOS/Linux: `export FINNHUB_API_KEY="YOUR_KEY"`
5. Run: `node server.js`
6. Open http://localhost:3000

Never put the API key inside `public/index.html`.

## Important
The displayed quote is provided by the market-data provider and may have licensing/delay limitations depending on your account/plan. This app does not execute real trades.

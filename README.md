## Live Crypto Price Tracker

A minimal, real-time price dashboard for BTC, ETH, SOL, BNB, and ZEC.

**Key Features**
- Live price updates via Binance public WebSocket stream (wss://stream.binance.com:9443)
- Displays current price (USD), 24h change percentage, and directional coloring (green/red/neutral)
- Extremely lightweight – pure HTML, CSS, and vanilla JavaScript
- No advertisements, no trackers, no analytics, no bloat
- Runs entirely in the browser – no backend or API keys required

**Live Site**  
https://livecrypto.pages.dev/

**How It Works**  
The application connects directly to Binance's official public WebSocket endpoint on port 9443 to subscribe to real-time ticker streams. Prices and 24h changes update instantly as market data arrives from Binance. All processing and rendering happen client-side in your browser.

**Why This Exists**  
Many popular trackers come with heavy interfaces, ads, or unnecessary features. This version focuses on speed, simplicity, and zero distractions for users who just need a quick glance at these five major assets. This is perfect for those with widescreen monitors who want a narrow browser window at the side of their screen to show this information.

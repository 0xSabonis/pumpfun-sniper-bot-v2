# Solana Token Sniper – Raydium & Pump.fun  

## 📌 Overview  

A high-speed Solana sniper bot built in Rust, optimized for same-block execution on Raydium and Pump.fun, with secure memory handling and multi-gRPC support via Helius & Yellowstone.

---

## ⚡ Key Features  

| Feature | Description |
|---------|------------|
| 🚀 **Speed & Efficiency** | Executes **low-latency** token snipes almost instantly. |
| 🔒 **Security & Stability** | Built with **Rust** for performance and reliability. |
| 📡 **Real-Time Monitoring** | Connects to **Helius & Yellowstone** for real-time updates. |
| 🛠 **Advanced Trading** | Supports **Jito-confirm** and **Jito-bundle** for optimized transactions. |
| 🤖 **Automated Strategy Execution** | Smart triggers for entry and exit based on real-time market conditions. |
| 📈 **Customizable Trading Parameters** | Users can set **buy/sell thresholds, slippage, and max gas fees**. |
| 🔄 **Auto-Sell & Stop-Loss** | Protect profits and minimize losses with configurable stop-loss settings. |
| 👩‍💻 **User-Friendly Interface** | Configurable **.env settings** and **intuitive CLI for easy navigation**. |
| 🔍 **Live Transaction Tracking** | Monitor trades in real-time with a detailed execution log. |
| 🏦 **Multi-Wallet Support** | Trade across multiple wallets for diversification and risk management. |
| 🛒 **Pre-Set Token Whitelist/Blacklist** | Avoid rug pulls and target only trusted tokens. |
| 🎯 **Smart AI Prediction (Future Feature)** | Integrate AI models to identify high-potential sniping targets. |


---


## 🎯 Trading Strategy  

The bot automatically buys when a user purchases $1,000+ of a token, sells when $300+ is sold, closes positions after 60 seconds, includes stop-loss protection, and dynamically adjusts strategy based on market trends, with all parameters configurable in .env.

---

## 📌 Setup & Configuration

### 1️⃣ Set Environment Variables
Create a `.env` file in the root directory and add the following settings:

```plaintext
PRIVATE_KEY=your_private_key
RPC_HTTPS=https://mainnet.helius-rpc.com/?api-key=your_api_key
SLIPPAGE=10
BUY_THRESHOLD=1000
SELL_THRESHOLD=300
TIME_EXCEED=60
```

### 2️⃣ Run the Bot
Execute the following command to start the bot:

```sh
cargo run --release
```

### 3️⃣ Configure Blocklist
To block specific traders, add wallet addresses to a text file:

```plaintext
0x1234567890abcdef
0xabcdef1234567890
```

---


## 📊 Test Results

- ✅ **Detected:** [View Transaction](https://solscan.io/tx/5o7ajnZ9CRf7FBYEvydu8vapJJDWtKCvRFiTUBmbeu2FmmDhAQQy3c9YFFhpTucr2SZcrf2aUsDanEVjYgwN9kBc)
- 🛒 **Bought:** [View Transaction](https://solscan.io/tx/3vgim3MwJsdtahXqfW2DrzTAWpVQ8EUTed2cjzHuqxSfUpfp72mgzZhiVosWaCUHdqJTDHpQaYh5xN7rkHGmzqWv)
- 📈 **Trade Analysis:** [DEX Screener](https://dexscreener.com/solana/A1zZXCq2DmqwVD4fLDzmgQ3ceY6LQnMBVokejqnHpump)


---


## 💬 Support  
**Telegram** | [@Sabonis](https://t.me/sabonis_24) 


---


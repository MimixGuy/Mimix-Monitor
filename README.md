# 🔍 Mimix Monitor

> **The Gunbot Trading Dashboard you always wanted.**

**Mimix Monitor** is a real-time web dashboard for Gunbot traders. It aggregates data from all your Gunbot instances and exchanges into a single, clean interface — giving you full visibility over your portfolio, PnL, positions, DCA risk, and more.

---

## 🚀 Live Demo

👉 **[demo.mimixmonitor.com](https://demo.mimixmonitor.com)** — explore the full dashboard with live simulated data. No login required.

---

## ⚡ How It Works

| Step | |
|---|---|
| **1. Connect** | Add your Gunbot instances in the Settings tab — just the folder path and exchange |
| **2. Monitor** | Mimix Monitor reads your data in real time and displays everything in one dashboard |
| **3. Profit** | Track PnL, manage risk, earn on idle capital, and get alerted before problems become losses |

No cloud. No API keys shared. No extra subscriptions. **Your data stays on your own server.**

---

## 🔒 Security

> Mimix Monitor is **100% read-only**. It never places orders, never touches your funds, and all data stays on your own server. Nothing is sent to external servers — it runs entirely on your VPS or machine.

---

## 🔹 What is Mimix Monitor?

Mimix Monitor connects directly to your Gunbot installation and displays everything in real time:

| Feature | Description |
|---|---|
| 📊 Portfolio overview | Total balance across all exchanges, live |
| 💰 Three-layer PnL | Exchange PnL + Gunbot PnL + Real PnL |
| 🎯 DCA Risk Engine | Grid analysis, capital floor, risk scoring |
| 🏦 Earn Module | Auto idle capital → Binance / KuCoin / MEXC / OKX interest |
| 🔍 24/7 Monitoring | Detects crashes, idle bots, and anomalies — Telegram alerts instantly |
| ⚖️ Bot vs Buy & Hold | Is your bot actually beating a passive hold strategy? |
| 🔔 Telegram alerts | Positions, PnL thresholds, dead pairs, and much more |
| 🌍 7 Languages | EN, ES, DE, FR, IT, PT, NL — language is never a barrier |
| 🌙 Dark mode | EUR/USD toggle · Responsive design |

---

## 🔹 Three-Layer PnL System

Most dashboards show you one number. Mimix Monitor shows you **three** — each telling a different part of the story:

| Metric | What it measures |
|---|---|
| 📉 **Exchange PnL** | Unrealized market movement on your open bags (price dropped = negative) |
| 📈 **Gunbot PnL** | Realized profits from completed buy/sell cycles |
| 💎 **Real PnL** | Exchange PnL + Gunbot PnL = the true net result |

```
Real PnL = Exchange PnL + Gunbot PnL
```

### Why This Matters

**🚨 Scenario A — False confidence (dangerous):**
> Gunbot PnL shows **+$200** this month.
> But your bags are down **−$800** due to market drawdown.
> **Real PnL = −$600** — you are actually losing money.
> Without Real PnL, you'd think the bot is doing great.

**🛡️ Scenario B — Bot is genuinely helping:**
> Market crashed. Your bags are down **−$1,000**.
> Gunbot PnL = **+$400** from completed trades during the dip.
> **Real PnL = −$600** — the bot reduced your loss by 40%.
> This is exactly what a bot should do.

**🚀 Scenario C — Winning on all fronts:**
> Market is up. Exchange PnL = **+$300** (bags gained value).
> Gunbot PnL = **+$150** from completed trades.
> **Real PnL = +$450** — price appreciation AND bot profits working together.

> 💡 A positive Gunbot PnL during a market crash means the bot is working correctly — generating realized profit while holding bags. Only Real PnL tells you whether you're truly ahead or behind.

---

## 🔹 Features

### 📊 Portfolio Overview
- Total USD balance across all exchanges, updated in real time
- Three-layer PnL for today, yesterday, week, month, year, and all time
- 90-day portfolio growth chart
- Exchange and asset class allocation breakdown (crypto, stocks, metals)

> **Example:** You run 5 Gunbot instances across Binance, KuCoin, MEXC, OKX, and Bybit. One screen shows your total portfolio, PnL by timeframe, and growth chart — no manual spreadsheet, no jumping between tabs.

---

### 🏦 Exchange Instances
- Per-exchange: balance, PnL, active pairs, open positions
- Per-pair: PnL history, position status, last orders, break-even price
- Dead pairs detection with configurable threshold
- Color-coded performance indicators

> **Example:** You notice BTC-USDT on KuCoin hasn't traded in 3 weeks. Mimix Monitor flags it as a dead pair automatically — no manual checking required.

---

### 🎯 DCA Risk Engine
- Visual DCA grid for every pair
- Capital floor detection — see exactly where your bot runs out of funds
- Risk scoring: 🟢 LOW / 🟡 MEDIUM / 🟠 HIGH / 🔴 CRITICAL
- Portfolio-level risk summary with capital at risk in USD

> **Example:** LINK is on DCA level 7 out of 10. Capital floor in 2 more drops. Risk: 🔴 CRITICAL. You know before the situation becomes irreversible — and can act.

---

### 🏦 Earn Module
- Tracks idle capital moved to Simple Earn (Binance, KuCoin, MEXC, OKX — more exchanges coming)
- Auto-subscribe / auto-redeem log with timestamps and amounts
- APY tracking and total interest earned

> 💡 **Your money never stops working.** Example: you have $10,000 but only $2,000 is actively deployed in trades. Without Mimix Monitor, the remaining $8,000 sits idle earning nothing. With Mimix Monitor, $7,500+ of that idle capital goes directly into Earn — generating interest around the clock until the bot actually needs it to buy. You can tune the thresholds to keep up to **99% of your capital working 24/7**. A unique tool that compounds your income over time.

---

### 🔍 24/7 Instance Monitoring
- Monitors all your Gunbot instances around the clock
- Detects crashes, bots that stopped trading, connectivity issues, and general anomalies
- Instant Telegram alert the moment something goes wrong

> **Example:** Your VPS restarts at 3am and Gunbot fails to reconnect. Mimix Monitor detects the instance is down and sends you a Telegram message within seconds. You fix it before missing a single trade.

---

### ⚖️ Bot vs Buy & Hold
- Compares your bot's performance against a static hold strategy
- Max drawdown, ROE, risk-adjusted returns
- Visual winner badge: 🤖 BOT WINS or 📦 BUY & HOLD WINS

> **Example:** ETH dropped 40% this quarter. A passive hold ROE: −40%. Your bot's ROE: −12% — still negative, but the bot reduced your loss by 70%. Bot wins, even in a bear market.

---

### 🔔 Alerts & Notifications
- Telegram bot integration — set up once, receive alerts forever
- Configurable alerts: open positions, PnL thresholds, CRITICAL risk, dead pairs, Earn events, and much more!
- **24/7 instance monitoring** — detects crashes, bots that stopped trading, and any anomaly across all your instances

---

### 🌍 7 Languages — Language Is Never a Barrier

Mimix Monitor is fully available in **English, Spanish, German, French, Italian, Portuguese, and Dutch**.

> Every label, chart, alert, and notification is translated. You always understand exactly what is happening with your portfolio — in your native language. And when Mimix AI launches, you will be able to query your portfolio and receive analysis in your own language. This is a game changer.

---

### 🔑 License Management
- Lifetime license tied to your wallet address
- Early Access and Standard plans
- Mimix AI license included for Early Access buyers
- Automated license delivery by email after payment

---

## 🔹 Pricing

| Plan | Price | Includes |
|---|---|---|
| ⭐ **Early Access** | **$299.95** one-time | Mimix Monitor lifetime + **Mimix AI FREE** |
| Standard *(after launch)* | $399.95 one-time | Mimix Monitor lifetime |

🛒 **[Buy Now — $299.95](https://www.mimixmonitor.com)**

> Early Access ends at launch. Price increases to $399.95 and Mimix AI is no longer included.

---

## 🔹 Mimix AI *(Coming Soon)*

Mimix AI is an intelligent assistant built specifically for Gunbot traders — available in **your native language**:

- 💬 Natural language queries — *"How is BTC doing this week?"* *"Which pair is my biggest risk right now?"*
- 📊 Portfolio distribution analysis — crypto, stocks, metals — all in one view
- 🧠 AI-powered strategy optimization — reduce risk and maximize returns across asset classes
- 🚨 Automatic anomaly detection — dead pairs, capital floor warnings, underperforming instances
- 📄 Weekly PDF performance reports — automated summary delivered to your inbox
- 🤖 Available exclusively to Early Access buyers at no extra cost

> **Example:** You have $50,000 split across BTC, ETH, Apple stock, and gold. Mimix AI analyzes your full portfolio and tells you: *"70% of your capital is in high-correlation assets — consider moving 15% to metals to reduce drawdown risk."* All in your language, all in one place.

---

## 📦 Installation

### 🐧 Linux VPS (recommended)

```bash
# 1. Upload the binary to your VPS (run this on your LOCAL machine)
scp /path/to/MimixMonitor-linux root@YOUR_VPS_IP:/root/mimix-monitor/

# 2. Connect and make it executable
ssh root@YOUR_VPS_IP
cd /root/mimix-monitor
chmod +x MimixMonitor-linux

# 3. Open the firewall port
ufw allow 2001/tcp

# 4. Install PM2 and start
npm install -g pm2
pm2 start /root/mimix-monitor/MimixMonitor-linux --name MimixMonitor
pm2 save && pm2 startup
```

Open **http://YOUR_VPS_IP:2001** → enter your wallet and license key → done.

> Full step-by-step guide included as `README-linux.txt` inside the ZIP.

---

### 🪟 Windows

1. Extract the ZIP
2. Double-click `MimixMonitor.exe`
3. Open **http://localhost:2001**
4. Enter your wallet and license key → done.

> Note: Windows may show a SmartScreen warning — click "More info" → "Run anyway".

---

### 🍎 macOS

```bash
chmod +x MimixMonitor-mac && ./MimixMonitor-mac
```

Open **http://localhost:2001** → enter your wallet and license key → done.

> Note: if macOS blocks the app, go to System Settings → Privacy & Security → Allow Anyway.

---

### ⚙️ Configuration

On first run, a `config.json` is created automatically next to the binary:

```json
{ "port": 2001 }
```

Change the port if needed, then restart. Everything else (wallet, license key, Gunbot instances, Telegram alerts) is configured **inside the dashboard** — no manual file editing required.

---

## 🔹 Roadmap

- [x] Multi-exchange dashboard
- [x] Three-layer PnL system
- [x] DCA Risk Engine
- [x] Earn module (Binance / KuCoin / MEXC / OKX)
- [x] 24/7 instance monitoring with Telegram alerts
- [x] Bot vs Buy & Hold comparison
- [x] License management system
- [x] Telegram notifications
- [x] Multi-language (7 languages)
- [ ] Mimix AI — natural language portfolio assistant (crypto, stocks, metals)
- [ ] Mobile app (iOS / Android)
- [ ] More exchange integrations (Bybit futures, Gate.io)
- [ ] Automated reporting (weekly PDF summary)
- [ ] More features on customer request

---

## 🔹 Community & Support

**💬 Your ideas matter.** Have a feature request, bug report or need help?

**👉 Telegram: [@MimixOfficial](https://t.me/MimixOfficial)**

---

## 🛍️ Get Mimix Monitor

🛒 **[Buy Mimix Monitor Early Access — $299.95](https://www.mimixmonitor.com)**
- ✅ Lifetime license · No subscription · All future updates included
- ✅ Mimix AI license included FREE (Early Access only)
- ✅ Payments via NOWPayments · Crypto only · License delivered by email automatically

---

*© 2026 Mimix Monitor — Built for Gunbot traders.*


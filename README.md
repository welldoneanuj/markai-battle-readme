# MarkAI Battle 🤖📈

> Four AI models walk into a stock market. Only one walks out right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head predicting NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening, the market decides who wins.

Humans can challenge the AIs too. May the best predictor win.

🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Current Leaderboard

*5 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **60%** | 3/5 |
| 🥈 | Claude Sonnet 4.6 | 20% | 1/5 |
| 🥉 | Gemini 2.5 Flash | 20% | 1/5 |
| 4️⃣ | GPT-4o | 20% | 1/5 |

> Early days. Grok is in front but the leaderboard is very much alive.

---

## 📅 Recent Results

| Date | Actual | NIFTY Close |
|------|--------|-------------|
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |
| 2026-04-08 | 🟢 UP | 23,997 |
| 2026-04-07 | 🟢 UP | 23,124 |

---

## ⚙️ How It Works

1. **Morning** — Each AI model is given NIFTY 50 market context (prev close, GIFT Nifty, global cues) and asked to predict: `UP`, `DOWN`, or `SIDEWAYS`
2. **Market hours** — Predictions are locked in. Session stays live and updates until 3:30 PM IST
3. **End of day** — NIFTY 50 closing price is fetched from NSE. The actual direction is calculated and each AI is scored
4. **Leaderboard** — Accuracy updates in real time on the live site

Predictions run daily on Indian market trading days. Holidays are handled automatically.

Humans can also submit their own predictions and compete directly against the AIs. 🧠 vs 🤖

---

## 🔧 Recent Changes

```
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
7bc651a  add CLAUDE.md — project guide for Claude Code sessions
106a10f  add .env and data/ to .gitignore
081f626  fix: build_log + README update on every deploy (not post-push hook)
```

---

## 🔨 Built in Public

Solo indie project. No team, no funding, no safety net — just vibes and commit logs.

The code is private for now but everything else is open: the predictions, the results, the leaderboard, and the journey. Follow along as this evolves from a weekend experiment into something interesting.

---

## 📡 Follow Along

- 🌐 **Live Arena:** [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram Bot:** Coming soon — daily prediction alerts straight to your phone
- 🐦 **Build logs & updates:** Follow [@welldoneanuj](https://github.com/welldoneanuj) on GitHub

---

*Last updated: 2026-04-15*
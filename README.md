# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head forecasting NIFTY 50 direction every morning — and get brutally scored by the market every evening. Humans can challenge them too.

🔴 **Live now →** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*Updated daily after market close. 8 sessions completed.*

| Rank | Model | Accuracy | Score |
|------|-------|----------|-------|
| 🥇 | Grok 4 | 62% | 5/8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3/8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3/8 |
| 4️⃣ | GPT-4o | 38% | 3/8 |

> Grok 4 is currently the only AI beating random chance. The market humbles everyone equally.

---

## 📅 Recent Results

| Date | Result | NIFTY Close |
|------|--------|-------------|
| 2026-04-17 | 🟢 UP | 24,354 |
| 2026-04-16 | 🟡 SIDEWAYS | 24,197 |
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |

---

## ⚙️ How It Works

1. **Every morning** before market open, all four AIs independently predict whether NIFTY 50 will close **UP**, **DOWN**, or **SIDEWAYS**
2. **Humans can predict too** — jump in and see if you can beat the bots
3. **At market close (3:30 PM IST)**, the actual result is fetched from NSE and scores are updated
4. **Leaderboard** tracks cumulative accuracy across all sessions
5. Repeat. Every. Day.

The AIs have no memory of their past failures. The leaderboard does. 😈

---

## 🔧 Recent Changes

```
6df5751  feat: analytics-driven tweet reviewer (VPS cron 8 AM IST)
bb7eb89  fix: twitter thread structure for better algorithmic reach
d7855c0  feat: cookie-based user sessions for human predictions
dd9c023  fix: NameError today_result → result in index() form handler
f446deb  fix: robust submit handler + global error logging in server.py
af00c01  fix: never show blank page during 9:15 AM → next-cron gap
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
```

Shipping fixes and features daily. This is what building in public looks like — messy, real, and moving fast.

---

## 📣 Follow Along

This is a solo indie project, built and shipped in public. No team. No funding. Just curiosity and too many API keys.

- 🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Updates on X/Twitter:** follow the daily prediction threads
- 💬 **Feedback?** Open an issue or just show up on the site and make a prediction

If the AIs are wrong today, they'll be wrong again tomorrow. Come watch. 🍿

---

*Last updated: 2026-04-18*
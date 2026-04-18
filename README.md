# MarkAI Battle ⚔️

> Four AI models walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head predicting the NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening the market decides. Humans can challenge the AIs too.

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Leaderboard

*8 sessions completed*

| Rank | Model | Accuracy | Score |
|------|-------|----------|-------|
| 🥇 | Grok 4 | 62% | 5/8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3/8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3/8 |
| 4️⃣ | GPT-4o | 38% | 3/8 |

Grok 4 is running away with it. The rest are in a three-way tie for second. Early days — things can still flip.

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

1. **Every morning** — all four AI models independently predict whether NIFTY 50 will close UP, DOWN, or SIDEWAYS from the previous day's close
2. **Humans can play too** — submit your own prediction before market opens and see how you stack up against the AIs
3. **End of day** — actual NIFTY close is fetched, predictions are scored, leaderboard updates
4. **Repeat daily** — one session per trading day, no restarts, no cherrypicking

The rules are simple. The market is not.

---

## 🛠️ Recent Changelog

```
d7855c0  feat: cookie-based user sessions for human predictions
dd9c023  fix: NameError today_result → result in index() form handler
f446deb  fix: robust submit handler + global error logging in server.py
af00c01  fix: never show blank page during 9:15 AM → next-cron gap
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
```

Lots of edge-case wrangling around market open/close timing. The gap between 9:15 AM and the first cron job is surprisingly annoying. Getting there. 🔧

---

## 📣 Follow Along

This is a **building in public** project — solo dev, real data, no fluff.

- 🌐 Watch the battles live → **[markai.garganuj.com](https://markai.garganuj.com)**
- 💬 Updates & discussion → drop a ⭐ on this repo to follow along

If you're into AI, markets, or just want to watch four language models argue with the stock market every day — you're in the right place.

---

*Last updated: 2026-04-18*
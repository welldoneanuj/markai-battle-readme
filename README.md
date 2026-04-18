# MarkAI Battle ⚔️

> Four AI models walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head predicting the NIFTY 50 market direction — UP, DOWN, or SIDEWAYS. Results are scored every evening. Humans can challenge the AIs too.

Built and run by one person, in public, one commit at a time.

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Leaderboard

*8 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **62%** | 5 / 8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3 / 8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3 / 8 |
| 4️⃣ | GPT-4o | 38% | 3 / 8 |

> Grok 4 is currently running away with it. The others are watching nervously.

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-17 | 🟢 UP | 24,354 |
| 2026-04-16 | 🟡 SIDEWAYS | 24,197 |
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |

---

## ⚙️ How It Works

1. **Every morning** — each AI model independently predicts NIFTY 50 direction for the day: `UP`, `DOWN`, or `SIDEWAYS`
2. **Each model reasons out loud** — predictions come with a short rationale based on news, trends, and vibes
3. **Market closes** — EOD price is fetched and compared against each prediction
4. **Scores update** — the leaderboard reflects cumulative accuracy across all sessions
5. **Humans can play too** — submit your own prediction and see how you stack up against the machines

Predictions run on weekdays *and* weekends (news doesn't take days off). A Telegram bot keeps followers in the loop daily.

---

## 🛠️ Recent Changes

```
e21e6fd  Merge PR #3 — tweet reviewer cron improvements
6e804ec  chore: auto-register tweet_reviewer cron on every deploy
c36a372  Merge PR #2 — CI/CD + test suite overhaul
4e98b25  fix: resolve all pyflakes lint errors blocking CI
a3e13a8  fix: run predict.py identically on weekends/holidays + CI/CD pipeline
         + test suite + cookie sessions + tweet restructure
3ed5845  fix: run predict.py identically on weekends/holidays — no special casing
cbdf449  fix: predict every 3h on weekends too — news can shift the trend
8d0c976  fix: send weekend preview to Telegram instead of silently skipping
```

The code is private for now, but the journey is fully public. Every messy fix, every failed CI run — all of it.

---

## 📣 Follow Along

This is a **building in public** project. If you're into AI, markets, or watching indie devs debug cron jobs at midnight — you'll fit right in.

- 🌐 Live arena: [markai.garganuj.com](https://markai.garganuj.com)
- 💬 Daily predictions on Telegram: *(link coming soon)*
- 🐙 This repo is public — star it if you want to see where this goes ⭐

---

*Last updated: 2026-04-18*
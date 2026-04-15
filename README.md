# MarkAI Battle ⚔️

> Four AI models walk into a stock market. Only one can be right.

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head every trading day — each predicting whether NIFTY 50 will close **UP**, **DOWN**, or **SIDEWAYS**. Humans can challenge them too. May the best intelligence win.

🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Live Leaderboard

*5 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | 60% | 3 / 5 |
| 🥈 | Claude Sonnet 4.6 | 20% | 1 / 5 |
| 🥉 | Gemini 2.5 Flash | 20% | 1 / 5 |
| 4️⃣ | GPT-4o | 20% | 1 / 5 |

> Early days. The rankings *will* shift.

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |
| 2026-04-08 | 🟢 UP | 23,997 |
| 2026-04-07 | 🟢 UP | 23,124 |

---

## ⚙️ How It Works

1. **Every morning** before market open, all four AI models independently predict NIFTY 50 direction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Each AI reasons** using available signals — GIFT Nifty, previous close, and market context
3. **At 3:30 PM IST**, the actual closing price is fetched and predictions are scored
4. **Accuracy compounds** over time — the leaderboard reflects every session since launch
5. **Humans can challenge** the AIs directly on the live site

No cherry-picking. No post-hoc edits. Predictions lock before the bell. 🔔

---

## 🔄 Changelog

```
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
7bc651a  add CLAUDE.md — project guide for Claude Code sessions
106a10f  add .env and data/ to .gitignore
```

*Building in public means shipping fixes in public too. 🛠️*

---

## 📣 Follow Along

This is a solo indie project — built, broken, and fixed in public.

- 🌐 **Live arena:** [markai.garganuj.com](https://markai.garganuj.com)
- 🔔 **Get daily results:** Telegram bot coming soon
- ⭐ **Star this repo** if you want to see where the leaderboard goes

The sample size is small. The stakes are imaginary. The competition is very real.

---

*Last updated: 2026-04-15 · Built with ☕ by [@welldoneanuj](https://github.com/welldoneanuj)*
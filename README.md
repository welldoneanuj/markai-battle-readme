# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head forecasting NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening the market decides. Humans can challenge them too.

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Current Leaderboard

*6 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **67%** | 4 / 6 |
| 🥈 | Claude Sonnet 4.6 | 33% | 2 / 6 |
| 🥉 | Gemini 2.5 Flash | 33% | 2 / 6 |
| 4️⃣ | GPT-4o | 33% | 2 / 6 |

Grok 4 is running away with it early. Plenty of sessions left for the others to fight back.

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |
| 2026-04-08 | 🟢 UP | 23,997 |

---

## ⚙️ How It Works

1. **Morning** — Each AI model receives the same market context (prev close, GIFT Nifty, global cues) and independently predicts: `UP` / `DOWN` / `SIDEWAYS`
2. **Market hours** — Predictions are locked once NSE opens at 9:15 AM IST
3. **Evening** — NIFTY 50 closing price is fetched at 3:30 PM IST and the session is scored
4. **Leaderboard** — Accuracy updates in real time on the live site
5. **You** — Humans can submit their own prediction and see how they stack up against the AIs

No fine-tuning. No hindsight. Raw daily predictions, publicly tracked.

---

## 🛠️ Recent Changelog

```
af00c01  fix: never show blank page during 9:15 AM → next-cron gap
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
7bc651a  add CLAUDE.md — project guide for Claude Code sessions
```

Shipping fixes daily. Building this live, rough edges and all. 🔧

---

## 📣 Follow Along

This is a solo indie project, built entirely in public. I share daily results, AI reasoning snippets, and behind-the-scenes dev updates.

- 🌐 **Live Arena** → [markai.garganuj.com](https://markai.garganuj.com)
- 🤖 **Telegram** → Coming soon
- 🐦 **Updates** → Follow the commits, they tell the story

If you find this interesting, star the repo and check back daily. The leaderboard is very much alive. 🚀

---

*Last updated: 2026-04-15*
# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head every trading day — each calling NIFTY 50's direction (UP / DOWN / SIDEWAYS) before the market opens. Scores are settled at 3:30 PM IST. No hand-waving. Just predictions and results.

Humans can challenge the AIs too. 👀

🔗 **[markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Live Leaderboard

> 7 sessions completed

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **57%** | 4 / 7 |
| 🥈 | Claude Sonnet 4.6 | 29% | 2 / 7 |
| 🥉 | Gemini 2.5 Flash | 29% | 2 / 7 |
| 4️⃣ | GPT-4o | 29% | 2 / 7 |

*Early days. The table will look very different in 30 sessions.*

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-16 | 🟡 SIDEWAYS | 24,197 |
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |

---

## ⚙️ How It Works

1. **Every trading morning** — each AI model independently analyzes market context and predicts NIFTY 50 direction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Market runs** — NIFTY does whatever NIFTY wants
3. **3:30 PM IST** — session closes, actual direction is recorded, scores updated
4. **Leaderboard updates** — accuracy tracked cumulatively across all sessions

Predictions are locked before 9:15 AM IST. No peeking, no revisions.

---

## 🛠️ Recent Changelog

```
f446deb  fix: robust submit handler + global error logging in server.py
af00c01  fix: never show blank page during 9:15 AM → next-cron gap
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
```

A lot of edge cases in a live market system. Shipping fixes daily. 🔧

---

## 👀 Follow Along

This is a solo indie project, built entirely in public. I share daily prediction results, model breakdowns, and behind-the-scenes updates.

- 🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram:** Follow the bot for daily prediction alerts *(coming soon)*
- 🐙 **Code:** Private for now — but the story is public

If you find this interesting, star the repo and check back. Things are just getting started. 🚀

---

*Last updated: 2026-04-17*
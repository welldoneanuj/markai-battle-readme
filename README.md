# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can win.

**[🔴 LIVE →](https://markai.garganuj.com)**

Every trading day, Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 each make a prediction: will NIFTY 50 go **UP**, **DOWN**, or **SIDEWAYS**? Results are scored at market close. Humans can challenge them too.

Built and run by one person. Completely in public.

---

## 🏆 Leaderboard

*6 sessions completed*

| Rank | Model | Accuracy | Score |
|------|-------|----------|-------|
| 🥇 | Grok 4 | 67% | 4 / 6 |
| 🥈 | Claude Sonnet 4.6 | 33% | 2 / 6 |
| 🥉 | Gemini 2.5 Flash | 33% | 2 / 6 |
| 4️⃣ | GPT-4o | 33% | 2 / 6 |

Grok 4 is out here making the others look like interns. Early days though.

---

## 📅 Recent Results

| Date | Result | NIFTY Close |
|------|--------|-------------|
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |
| 2026-04-08 | 🟢 UP | 23,997 |

---

## ⚙️ How It Works

1. **Every morning** — each AI receives the same market context and independently predicts NIFTY 50 direction for the session
2. **Predictions lock** once the market opens at 9:15 AM IST
3. **At 3:30 PM IST** — market closes, actual direction is recorded, scores are updated
4. **Leaderboard updates** automatically. No human intervention in scoring.

Humans can also submit their own predictions and compete directly against the AIs on the live site.

---

## 🔧 Recent Changes

```
af00c01  fix: never show blank page during 9:15 AM → next-cron gap
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
7bc651a  add: CLAUDE.md — project guide for Claude Code sessions
```

Lots of edge cases when you're building around live market hours. Getting there.

---

## 🙋 Challenge the AIs

Think you can beat GPT-4o? Prove it.

Head to **[markai.garganuj.com](https://markai.garganuj.com)**, submit your prediction before 9:15 AM IST, and see where you land on the leaderboard by evening.

---

## 📡 Follow Along

This is a build-in-public project. New features, fixes, and leaderboard drama get shared as it happens.

- 🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram:** Coming soon
- 🐦 **Updates:** Follow [@welldoneanuj](https://github.com/welldoneanuj) on GitHub

---

*Last updated: 2026-04-15*
# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 compete head-to-head every trading day — each calling NIFTY 50 direction (UP / DOWN / SIDEWAYS) before market open. Results are scored at EOD. Humans can challenge the AIs too.

🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*5 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | 60% | 3 / 5 |
| 🥈 | Claude Sonnet 4.6 | 20% | 1 / 5 |
| 🥉 | Gemini 2.5 Flash | 20% | 1 / 5 |
| 4️⃣ | GPT-4o | 20% | 1 / 5 |

Early days. Grok is ahead, but the market has a long memory. 👀

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

1. **Every morning** before market open, all four AIs independently predict NIFTY 50 direction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Each AI reasons out loud** — no black-box answers, you can read their rationale
3. **At 3:30 PM IST** (market close), the actual outcome is recorded and predictions are scored
4. **Leaderboard updates daily** — accuracy is tracked over time
5. **Humans can play too** — think you can beat the AIs? Jump in on the live site

It's part experiment, part game, part honest look at whether AI is actually useful for market calls.

---

## 🔧 Recent Changes

```
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
7bc651a  add CLAUDE.md — project guide for Claude Code sessions
081f626  fix: build_log + README update on every deploy (not post-push hook)
e47c01f  fix: health check port 8000 → 8080
```

Lots of plumbing fixes lately. The fun part of building in public — you see the messy middle, not just the highlight reel.

---

## 📣 Follow Along

This is a solo indie project, built and run in public. New sessions go live every trading day.

- 🌐 **Arena:** [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Updates & commentary:** follow the build on X / Twitter
- 💬 **Telegram:** daily prediction alerts coming soon

If you find this interesting, star the repo and check back — the real test is over hundreds of sessions, not five.

---

*Last updated: 2026-04-15*
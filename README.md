# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head forecasting NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening the market decides. Humans can challenge them too.

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

1. **Every morning** — each AI model independently predicts whether NIFTY 50 will close UP, DOWN, or SIDEWAYS
2. **Market opens** — no peeking, no changing answers
3. **EOD** — actual close is recorded, predictions are scored
4. **Leaderboard updates** — accuracy tracked cumulatively over time
5. **Humans welcome** — you can submit your own prediction and go up against the AIs

Simple rules. Real data. No excuses.

---

## 🔄 Recent Changelog

```
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
7bc651a  add CLAUDE.md — project guide for Claude Code sessions
106a10f  add .env and data/ to .gitignore
081f626  fix: build_log + README update on every deploy (not post-push hook)
e47c01f  fix: health check port 8000 → 8080
5d9ceb9  add CI/CD: GitHub Actions deploy with health check + auto-rollback
1af4c0a  add shareable card, build-log README auto-update, milestone tweets
```

---

## 👀 Follow Along

This is a solo indie project, built entirely in public. No team. No funding. Just curiosity and a stubborn belief that this is fun.

- 🌐 **Live arena:** [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Daily updates & predictions:** Telegram bot at the live site
- 🐙 **This repo:** Public changelog and leaderboard — code stays private for now

If you find this interesting, share it. If the AIs embarrass themselves, enjoy it. Either way, check back tomorrow — the market opens again.

---

*Last updated: 2026-04-15*
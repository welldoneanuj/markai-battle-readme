# MarkAI Battle ⚔️

> Four AIs walk into a trading arena. Only one can predict the market. Humans can fight too.

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head every morning — each predicting whether NIFTY 50 will close **UP**, **DOWN**, or **SIDEWAYS**. Results are scored at EOD. No retries. No excuses.

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Leaderboard — 5 Sessions In

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | 60% | 3/5 |
| 🥈 | Claude Sonnet 4.6 | 20% | 1/5 |
| 🥉 | Gemini 2.5 Flash | 20% | 1/5 |
| 4️⃣ | GPT-4o | 20% | 1/5 |

> Early days. The leaderboard is volatile. Come back in 30 sessions.

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

1. **Every market morning** — each AI independently predicts NIFTY 50 direction: `UP` / `DOWN` / `SIDEWAYS`
2. **No peeking** — predictions are locked before market open
3. **EOD scoring** — actual close price determines the winner for the day
4. **Leaderboard updates live** — accuracy tracked cumulatively across all sessions
5. **Humans can challenge too** — think you can beat GPT-4o? Prove it on the live site

The system runs fully automated on a VPS with a Python backend, daily prediction agents, and a CI/CD pipeline with health checks and auto-rollback.

---

## 🔧 Recent Changelog

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

> This README is auto-updated on every deploy. What you see is what's live. 🚀

---

## 📣 Follow Along

I'm building this entirely in public — solo, nights and weekends, figuring it out as I go.

- 🌐 **Live Arena** → [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Daily predictions & updates** → Telegram bot (coming soon)
- 🐦 **Build log & milestones** → [@welldoneanuj](https://x.com/welldoneanuj)

If this project interests you, star the repo and watch the leaderboard shift over time. That's the whole point.

---

*Last updated: 2026-04-15*
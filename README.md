# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head predicting the NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they make their call. Every evening, the market decides who was right.

Humans can challenge the AIs too. 🧠

🔴 **Live now →** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*After 5 sessions — the market doesn't lie.*

| Rank | AI | Accuracy | Correct |
|------|----|----------|---------|
| 🥇 | **Grok 4** | 60% | 3 / 5 |
| 🥈 | Claude Sonnet 4.6 | 20% | 1 / 5 |
| 🥉 | Gemini 2.5 Flash | 20% | 1 / 5 |
| 4️⃣ | GPT-4o | 20% | 1 / 5 |

Early days. The standings will get interesting. 👀

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

1. **Every morning** — each AI independently predicts NIFTY 50 direction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Market opens** at 9:15 AM IST, closes at 3:30 PM IST
3. **EOD scoring** — predictions are locked and scored against the actual close
4. **Leaderboard updates** daily, no human in the loop
5. **You can play too** — submit your own prediction and see how you stack up against the AIs

Simple rules. Real market. No handicaps.

---

## 🔧 Recent Changes

```
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
2049891  fix: remove Breeze/Kite dependency, add holiday calendar, agent mode, stable data sources
7bc651a  add CLAUDE.md — project guide for Claude Code sessions
106a10f  add .env and data/ to .gitignore
081f626  fix: build_log + README update on every deploy (not post-push hook)
e47c01f  fix: health check port 8000 → 8080
5d9ceb9  add CI/CD: GitHub Actions deploy with health check + auto-rollback
```

Building fast, fixing faster. 🛠️

---

## 📣 Follow Along

This is a solo indie project, built entirely in public. Every bug, every fix, every leaderboard swing — it's all happening live.

- 🌐 **Live site** → [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram** → Daily predictions & results drop here *(coming soon)*
- 🐦 Follow the build journey on X / Twitter

If you find this interesting, star the repo. It means a lot when you're building alone. ⭐

---

*Last updated: 2026-04-15*
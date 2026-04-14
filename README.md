# MarkAI Battle 🤖⚔️

> Four AIs walk into the stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head predicting the NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening the market judges.

Humans can challenge the AIs too. The market doesn't care who built you.

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Leaderboard

*After 6 sessions*

| Rank | Model | Accuracy | Score |
|------|-------|----------|-------|
| 🥇 | Grok 4 | 67% | 4/6 |
| 🥈 | Claude Sonnet 4.6 | 33% | 2/6 |
| 🥉 | Gemini 2.5 Flash | 33% | 2/6 |
| 4️⃣ | GPT-4o | 33% | 2/6 |

> Grok 4 is currently the one to beat. Let's see if that holds.

---

## 📅 Recent Results

| Date | Result | NIFTY Close |
|------|--------|-------------|
| 2026-04-14 | 🔴 DOWN | 23,843 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |
| 2026-04-08 | 🟢 UP | 23,997 |

---

## ⚙️ How It Works

1. **Every morning** — each AI model is prompted with recent NIFTY data and makes a directional prediction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Market closes** — NIFTY 50 EOD price is recorded
3. **Scoring** — predictions are graded. Correct = point. Wrong = nothing. No partial credit
4. **Leaderboard updates** — scores, streaks, and accuracy refresh automatically
5. **Humans welcome** — you can submit your own prediction and go up against the models

No fine-tuning. No special market data. Just raw reasoning against a live market.

---

## 🛠️ Recent Changelog

```
106a10f  add .env and data/ to .gitignore
081f626  fix: build_log + README update on every deploy (not post-push hook)
e47c01f  fix: health check port 8000 → 8080
5d9ceb9  add CI/CD: GitHub Actions deploy with health check + auto-rollback
1af4c0a  add shareable card, build-log README auto-update, milestone tweets
6db8ed0  initial commit — full MarkAI Battle stack
```

Building in public means shipping rough edges and fixing them in daylight. 🌞

---

## 📣 Follow Along

This is a solo indie project — built, deployed, and maintained by one person. New features ship when they're ready. Predictions go out every trading day.

- 🌐 **Live arena** → [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram** → Get daily predictions delivered to you *(bot link on the site)*
- 🐦 **Updates** → Milestone tweets auto-post as the leaderboard shifts

If you find this interesting, star the repo and check back. It's just getting started.

---

*Last updated: 2026-04-14*
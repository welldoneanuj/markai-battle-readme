# MarkAI Battle 🤖⚔️

> Four AI models walk into a stock market. Only one can be right.

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head every trading day — each calling NIFTY 50's direction (UP / DOWN / SIDEWAYS) before market open. Scores are settled at EOD. Humans can challenge the AIs too.

Built and run solo, in public. No hype — just data.

🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*6 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **67%** | 4 / 6 |
| 🥈 | Claude Sonnet 4.6 | 33% | 2 / 6 |
| 🥉 | Gemini 2.5 Flash | 33% | 2 / 6 |
| 4️⃣ | GPT-4o | 33% | 2 / 6 |

> Early days. The leaderboard will get interesting fast.

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-14 | 🔴 DOWN | 23,843 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |
| 2026-04-08 | 🟢 UP | 23,997 |

---

## ⚙️ How It Works

1. **Every morning** before market open, all four AI models independently predict NIFTY 50's direction — `UP`, `DOWN`, or `SIDEWAYS`
2. **Each AI explains its reasoning** — macro context, technicals, sentiment, whatever it thinks matters
3. **Market closes** → actual direction is recorded
4. **Scores update** on the live leaderboard automatically
5. **Humans can play too** — submit your own prediction and see how you stack up against the AIs

Simple rules. Real market. No do-overs.

---

## 🛠️ Recent Changelog

```
081f626  fix: build_log + README update on every deploy (not post-push hook)
e47c01f  fix: health check port 8000 → 8080
5d9ceb9  add CI/CD: GitHub Actions deploy with health check + auto-rollback
1af4c0a  add shareable card, build-log README auto-update, milestone tweets
6db8ed0  initial commit — full MarkAI Battle stack
```

> This README is auto-updated on every deploy. The build log keeps itself honest.

---

## 📣 Follow Along

This is a solo indie project, built entirely in public. Every deploy, every insight, every time an AI embarrasses itself on a red day — I share it.

- 🌐 **Live Arena** → [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram** → Daily predictions + results drop here *(link coming soon)*
- 🐦 **Updates** → Milestone moments get tweeted in real time

If this project interests you, watch the repo. More AIs, more markets, and human vs. AI tournaments are on the roadmap.

---

*Last updated: 2026-04-14*
# MarkAI Battle ⚔️

> Four AIs walk into a trading arena. Only one can predict the market best.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head forecasting the NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Predictions locked in every morning. Scores settled at EOD. No excuses.

Humans can challenge the AIs too. Think you can beat them? 👀

🔴 **Live →** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard *(13 sessions)*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | GPT-4o | 46% | 6 / 13 |
| 🥈 | Grok 4 | 46% | 6 / 13 |
| 🥉 | Gemini 2.5 Flash | 38% | 5 / 13 |
| 4️⃣ | Claude Sonnet 4.6 | 31% | 4 / 13 |

> Turns out predicting markets is hard. Even for the smartest AIs on the planet.

---

## 📅 Recent Results

| Date | Result | NIFTY Close |
|------|--------|-------------|
| 2026-04-24 | 🔴 DOWN | 23,898 |
| 2026-04-23 | 🔴 DOWN | 24,173 |
| 2026-04-22 | 🔴 DOWN | 24,378 |
| 2026-04-21 | 🟢 UP | 24,577 |
| 2026-04-20 | 🟡 SIDEWAYS | 24,365 |

---

## ⚙️ How It Works

1. **Every morning** — each AI independently analyzes overnight news, macro signals, and recent price action
2. **Prediction locked** — each model outputs one call: `UP`, `DOWN`, or `SIDEWAYS`
3. **Market closes** — NIFTY 50 EOD price is fetched and the actual direction is determined
4. **Scores updated** — correct calls earn a point, leaderboard updates automatically
5. **Repeat** — same time tomorrow ☀️

Humans can jump in too via a challenge link — pick your direction and see how you stack up against the AIs.

---

## 🛠️ Recent Changes

```
8b611bc  fix: SSH port 2222 for all deploy/smoke/notify steps
0ba0bdb  fix: use prefill_name (not active_name) in challenge URL
9e26767  feat: challenge link — dare others to predict NIFTY against you
8f3be2c  fix(build_log): robust Twitter 403 — parse error code, seconds+random retry suffix
c7e9064  fix(news): replace broken RSS feeds with Google News RSS, update free model chain
349f09a  fix: fetch news fresh on every predict run — no caching
```

---

## 🧑‍💻 Building in Public

This is a solo indie project — one dev, one idea, shipping daily. The code is private for now but the journey isn't. Every bug, every fix, every bad AI prediction — all of it plays out in the open.

If you're curious about how it's built, what breaks, or what's coming next — follow along.

---

## 📡 Follow Along

| | |
|---|---|
| 🌐 Live Arena | [markai.garganuj.com](https://markai.garganuj.com) |
| 🐦 Twitter / X | Updates posted after each session |

---

*Last updated: 2026-04-27*
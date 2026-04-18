# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head every trading day — each calling the NIFTY 50 direction (UP / DOWN / SIDEWAYS) before market open. Results are settled at EOD. Humans can challenge them too.

🔴 **Live now →** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*After 8 completed sessions*

| Rank | Model | Accuracy | Score |
|------|-------|----------|-------|
| 🥇 | Grok 4 | 62% | 5 / 8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3 / 8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3 / 8 |
| 4️⃣ | GPT-4o | 38% | 3 / 8 |

Grok is cooking. The others are chasing. 👀

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-17 | 🟢 UP | 24,354 |
| 2026-04-16 | 🟡 SIDEWAYS | 24,197 |
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |

---

## ⚙️ How It Works

1. **Every morning** (before 9:15 AM IST), all four AIs submit their NIFTY 50 prediction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Humans can play too** — submit your own prediction on the live site before market opens
3. **At end of day**, results are locked based on actual NIFTY close vs previous close
4. **Scores update** on the leaderboard. The best AI (and human) over time wins bragging rights

Simple. Brutal. Honest.

---

## 🛠️ Recent Changelog

| Commit | Change |
|--------|--------|
| `db304f5` | fix: use free OpenRouter model chain instead of paid Claude for tweet reviewer |
| `6df5751` | feat: analytics-driven tweet reviewer running via VPS cron at 8 AM IST |
| `bb7eb89` | fix: twitter thread structure tuned for better algorithmic reach |
| `d7855c0` | feat: cookie-based user sessions for human predictions |
| `dd9c023` | fix: NameError `today_result → result` in `index()` form handler |
| `f446deb` | fix: robust submit handler + global error logging in server.py |
| `af00c01` | fix: no more blank pages during the 9:15 AM → next-cron gap |
| `182f753` | fix: predictions always target the next session, never today once market opens |

> Building in public means shipping fixes in public too. No shame. 🔧

---

## 📣 Follow Along

This is a solo indie project, built and iterated on daily. If you're into AI, markets, or just watching robots argue about stocks — come hang.

- 🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Updates on X/Twitter** — follow the daily AI vs market drama
- 💬 **Telegram bot** — *coming soon*

If you find this fun or useful, a ⭐ on the repo goes a long way.

---

*Last updated: 2026-04-18*
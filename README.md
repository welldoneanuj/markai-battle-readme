# MarkAI Battle ⚔️

> Four AI models walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head predicting the NIFTY 50 direction — UP 🟢, DOWN 🔴, or SIDEWAYS 🟡. Results are scored at end of day. Humans can challenge the AIs too.

Built and run by a solo indie dev. Shipping in public, one session at a time.

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Leaderboard

*After 8 completed sessions*

| Rank | Model | Accuracy | Score |
|------|-------|----------|-------|
| 🥇 | **Grok 4** | 62% | 5 / 8 |
| 🥈 | **Claude Sonnet 4.6** | 38% | 3 / 8 |
| 🥉 | **Gemini 2.5 Flash** | 38% | 3 / 8 |
| 4️⃣ | **GPT-4o** | 38% | 3 / 8 |

> Grok 4 is quietly running away with this. The others are in a three-way tie for second. Market humbles everyone equally.

---

## 📅 Recent Results

| Date | Result | NIFTY Close |
|------|--------|-------------|
| 2026-04-17 | 🟢 UP | 24,354 |
| 2026-04-16 | 🟡 SIDEWAYS | 24,197 |
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |

---

## ⚙️ How It Works

1. **Every morning (pre-market)** — all four AIs submit their NIFTY 50 direction prediction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Humans can play too** — visit the live site before 9:15 AM IST and submit your own call
3. **Market closes** — NIFTY EOD price is recorded and the true direction is determined
4. **Scores update** — each correct prediction earns a point; leaderboard refreshes daily
5. **Repeat** — every trading day, forever (or until one AI goes full legendary)

No fancy ML pipelines. Just raw reasoning from frontier models, scored by the market. Brutally fair.

---

## 🛠️ Recent Changelog

| Commit | Change |
|--------|--------|
| `db304f5` | fix: use free OpenRouter model chain instead of paid Claude for tweet reviewer |
| `6df5751` | feat: analytics-driven tweet reviewer (VPS cron at 8 AM IST) |
| `bb7eb89` | fix: twitter thread structure optimised for algorithmic reach |
| `d7855c0` | feat: cookie-based user sessions for human predictions |
| `dd9c023` | fix: NameError `today_result → result` in `index()` form handler |
| `f446deb` | fix: robust submit handler + global error logging in server.py |
| `af00c01` | fix: never show blank page during 9:15 AM → next-cron gap |
| `182f753` | fix: predictions always target next session, never today once market opens |

> Real indie dev hours. Ship, break, fix, repeat. 🔧

---

## 📣 Follow Along

This is a **building in public** project. Every session, every bug, every leaderboard shift — documented live.

- 🌐 **Live Arena** → [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Twitter/X updates** → follow [@welldoneanuj](https://x.com/welldoneanuj) *(daily prediction threads)*
- ⭐ **Star this repo** if you want to see who wins by end of year

The code is private for now — but the predictions, results, and journey are fully public.

---

*Last updated: 2026-04-18*
# MarkAI Battle ⚔️

> Four AIs. One market. One winner. Every day.

**[🔴 Live Arena → markai.garganuj.com](https://markai.garganuj.com)**

---

## What Is This?

Every morning before market open, I pit **Claude Sonnet 4.6**, **GPT-4o**, **Gemini 2.5 Flash**, and **Grok 4** against each other — each making a blind prediction on NIFTY 50 direction (UP / DOWN / SIDEWAYS). At 3:30 PM IST, the market closes and we find out who was right.

**Humans can challenge the AIs too.** Jump in, make your prediction, and see if you can outperform a frontier model.

Built and run solo. All in public.

---

## 🏆 Live Leaderboard

*8 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **62%** | 5 / 8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3 / 8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3 / 8 |
| 4️⃣ | GPT-4o | 38% | 3 / 8 |

Grok 4 is quietly running away with it. Early days, but the gap is real.

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

```
Every trading day:

  08:45 AM IST  →  AI agents are prompted independently
                    Each predicts: UP / DOWN / SIDEWAYS
                    + a short reasoning blurb

  09:15 AM IST  →  Predictions locked. Market opens.
                    Human predictions accepted until open.

  03:30 PM IST  →  Market closes. Result recorded.
                    Scores updated. Leaderboard refreshes.

  Evening       →  Twitter thread posted with the day's breakdown
```

Each AI reasons from the same base context — prior close, GIFT Nifty signal, and recent trend — with no coordination between models. Pure blind prediction.

---

## 🛠️ Recent Changelog

| Commit | Change |
|--------|--------|
| `bb7eb89` | fix: Twitter thread structure for better algorithmic reach |
| `d7855c0` | feat: cookie-based user sessions for human predictions |
| `dd9c023` | fix: NameError `today_result → result` in index() form handler |
| `f446deb` | fix: robust submit handler + global error logging in server.py |
| `af00c01` | fix: never show blank page during 9:15 AM → next-cron gap |
| `182f753` | fix: predictions always target next session, never today once market opens |
| `14d6771` | fix: use NSE allIndices as primary for GIFT Nifty and prev_close |
| `5a5f517` | fix: predict.py keeps updating today's session until 3:30 PM IST |

Lots of fixing. That's indie dev. Ship, break, fix, repeat. 🔧

---

## 📡 Follow Along

This is a **building in public** project. Every session, every bug, every leaderboard shift — documented as it happens.

- 🌐 **Live site** → [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Updates on X** → Follow [@welldoneanuj](https://x.com/welldoneanuj) for daily prediction threads
- ⭐ **Star this repo** if you want to watch the journey

---

*Last updated: 2026-04-18*
# MarkAI Battle ⚔️

> Four AI models walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head forecasting NIFTY 50 direction — UP 🟢, DOWN 🔴, or SIDEWAYS 🟡. Scored against real market close. Humans can challenge the AIs too.

🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*8 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | **Grok 4** | 62% | 5 / 8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3 / 8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3 / 8 |
| 4️⃣ | GPT-4o | 38% | 3 / 8 |

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

1. **Every morning** before market open, all four AIs independently predict the NIFTY 50 direction for the day
2. **You can challenge them too** — submit your own prediction before 9:15 AM IST
3. **At 3:30 PM IST**, the market closes and results are locked in
4. **Scores update** on the leaderboard — no do-overs, no excuses

Each AI reasons from market context. The scoreboard is brutally honest.

---

## 🔄 Recent Changes

```
d7855c0  feat: cookie-based user sessions for human predictions
dd9c023  fix: NameError today_result → result in index() form handler
f446deb  fix: robust submit handler + global error logging in server.py
af00c01  fix: never show blank page during 9:15 AM → next-cron gap
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec23  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
```

A lot of "fix" commits. That's what building in public looks like. 🙃

---

## 📣 Follow Along

This is a solo indie project, built and iterated in the open. New features, blunders, and leaderboard upsets — all happening live.

- 🌐 **Arena:** [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Updates:** Follow [@welldoneanuj](https://github.com/welldoneanuj) for build logs

Can you beat the AIs? Come find out.

---

*Last updated: 2026-04-18*
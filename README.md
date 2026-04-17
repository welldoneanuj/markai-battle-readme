# MarkAI Battle 🤖⚔️

> Four AI models. One market. Zero mercy.

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head every trading day — each predicting whether NIFTY 50 will close **UP**, **DOWN**, or **SIDEWAYS**. Results are scored at end of day. No cherry-picking. No excuses.

Humans can challenge the AIs too. 👀

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Leaderboard *(7 sessions)*

| Rank | Model | Win Rate | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | 57% | 4 / 7 |
| 🥈 | Claude Sonnet 4.6 | 29% | 2 / 7 |
| 🥉 | Gemini 2.5 Flash | 29% | 2 / 7 |
| 4️⃣ | GPT-4o | 29% | 2 / 7 |

*Early days. The standings will shift. They always do.*

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-16 | 🟡 SIDEWAYS | 24,197 |
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |
| 2026-04-10 | 🟢 UP | 24,051 |
| 2026-04-09 | 🔴 DOWN | 23,775 |

---

## ⚙️ How It Works

1. **Every morning** before market open, all four AI models are independently prompted to predict NIFTY 50 direction for the day
2. **Predictions lock in** once the market opens at 9:15 AM IST — no take-backs
3. **At 3:30 PM IST**, the actual closing direction is fetched from NSE and each model is scored
4. **Leaderboard updates** with win rates across all sessions
5. **You can play too** — submit your own prediction before market open and see how you stack up against the AIs

No fine-tuning. No hindsight. Just raw predictions, every single day.

---

## 🛠️ Recent Changelog

```
dd9c023  fix: NameError today_result → result in index() form handler
f446deb  fix: robust submit handler + global error logging in server.py
af00c01  fix: never show blank page during 9:15 AM → next-cron gap
182f753  fix: predictions always target next session, never today once market opens
14d6771  fix: use NSE allIndices as primary for GIFT Nifty and prev_close
5a5f517  fix: predict.py keeps updating today's session until 3:30 PM IST
1c3ec25  fix: server.py shows today's session until 3:30 PM IST, not 9:15 AM
f34f847  fix: server.py startup migration for mode column — prevents deploy crash
```

*Real talk: the first week of a live project is just a parade of edge cases you never thought about. Getting there.*

---

## 📡 Follow Along

This is a **building-in-public** project by a solo indie dev. Everything runs live — the wins, the bugs, the weird market days.

- 🌐 **Live Arena** → [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram** → Updates & daily results *(coming soon)*
- 🐙 **Code** → Private for now, but the journey is public

If you find this interesting, drop a ⭐ and check back — this thing is just getting started.

---

*Last updated: 2026-04-17*
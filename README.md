# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head predicting the NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening the market judges.

Humans can challenge the AIs too. May the best mind win. 🧠

🔴 **Live:** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*(After 9 sessions)*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | 56% | 5 / 9 |
| 🥈 | Gemini 2.5 Flash | 44% | 4 / 9 |
| 🥉 | GPT-4o | 44% | 4 / 9 |
| 4️⃣ | Claude Sonnet 4.6 | 33% | 3 / 9 |

> Nobody's crushing it yet. The market humbles everyone equally.

---

## 📅 Recent Results

| Date | Outcome | NIFTY Close |
|------|---------|-------------|
| 2026-04-20 | 🟡 SIDEWAYS | 24,365 |
| 2026-04-17 | 🟢 UP | 24,354 |
| 2026-04-16 | 🟡 SIDEWAYS | 24,197 |
| 2026-04-15 | 🟢 UP | 24,231 |
| 2026-04-13 | 🔴 DOWN | 23,843 |

---

## ⚙️ How It Works

1. **Every morning** — all four AIs independently analyze market signals and predict NIFTY 50 direction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Each AI** gets fresh news on every run — no caching, no stale context
3. **End of day** — actual NIFTY close is recorded and predictions are scored
4. **Leaderboard updates** — accuracy tracked cumulatively across all sessions
5. **Humans can play too** — submit your own prediction and see how you stack up against the machines

No cheating. No hindsight. Just predictions, locked in before market open.

---

## 🛠️ Recent Changelog

```
91aaefd  Merge PR #7 — fresh news fetch fix
349f09a  fix: fetch news fresh on every predict run — no caching
415c35a  Merge PR #6
dca15cc  feat: add #BuildInPublic #IndieHacker to build-log tweet
46d8891  Merge PR #5
2643908  feat: split build-log tweet into thread — no link in tweet 1
7f053a4  Merge PR #4
c3f4512  fix: retry duplicate tweet with timestamp suffix on 403
```

Small fixes, daily shipping. That's the vibe. 🚢

---

## 👀 Follow Along

This is a solo indie project, built and iterated on in public. Every session, every fix, every embarrassing loss to a chatbot — it's all out there.

- 🌐 **Live site** → [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Build log** → Follow on Twitter/X for daily prediction threads with `#BuildInPublic #IndieHacker`
- 💬 **Get alerts** → Telegram bot coming soon

If you find this interesting, star the repo, share it, or just come back tomorrow to see if Grok 4 keeps its lead. 🌟

---

*Last updated: 2026-04-20*
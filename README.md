# MarkAI Battle ⚔️

> Four AIs walk into a stock market. Only one can be right.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head forecasting NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening the market judges.

Humans can challenge them too. 👀

🔴 **Live →** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*8 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **62%** | 5 / 8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3 / 8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3 / 8 |
| 4️⃣ | GPT-4o | 38% | 3 / 8 |

Grok 4 is out front — but 8 sessions is still early days. The leaderboard can flip any week.

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

1. **Every morning** — each AI independently predicts NIFTY 50 direction: `UP`, `DOWN`, or `SIDEWAYS`
2. **Market closes** — actual EOD price determines the ground truth
3. **Score is updated** — correct predictions increment each AI's win count
4. **Weekends too** — predictions run every 3 hours on weekends since news can still shift the trend
5. **Results are posted** to the live site and pushed to Telegram automatically

No cherry-picking. No post-hoc edits. Predictions are locked in before the market opens.

---

## 🔄 Recent Changes

```
c36a372  Merge PR #2 — CI/CD stabilisation
4e98b25  fix: resolve all pyflakes lint errors blocking CI
a3e13a8  fix: run predict.py identically on weekends/holidays + CI/CD pipeline
         + test suite + cookie sessions + tweet restructure
3ed5845  fix: no special-casing for weekends — same flow every day
cbdf449  fix: predict every 3h on weekends — news can shift the trend
8d0c976  fix: send weekend preview to Telegram instead of silently skipping
734f72b  ci: full CI/CD pipeline — lint → test → deploy → smoke-test
b434012  feat: pytest test suite — runs as pre-deploy gate on every push
```

Shipping fast, breaking things responsibly. 🚢

---

## 📣 Follow Along

This is a solo indie project, built and run in public. I share daily results, model breakdowns, and behind-the-scenes updates.

- 🌐 **Live site** → [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram** → Get daily predictions & results delivered to you
- 🐦 **Updates** — follow the build journey as it happens

If you find this interesting, drop a ⭐ — it genuinely helps.

---

*Last updated: 2026-04-18*
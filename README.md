# MarkAI Battle ⚔️

> Four AI models. One market. Daily predictions. Who sees the future best?

**MarkAI Battle** is a live prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head every trading day — each calling NIFTY 50 direction (UP / DOWN / SIDEWAYS) before the market opens. Results are scored at EOD. Humans can challenge the AIs too.

🌐 **Live site:** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*8 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **62%** | 5 / 8 |
| 🥈 | Claude Sonnet 4.6 | 38% | 3 / 8 |
| 🥉 | Gemini 2.5 Flash | 38% | 3 / 8 |
| 4️⃣ | GPT-4o | 38% | 3 / 8 |

Grok 4 leads early — but it's still anyone's game.

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

1. **Every morning** — each AI model receives the same market context and independently predicts NIFTY 50 direction for the day: `UP`, `DOWN`, or `SIDEWAYS`
2. **Market closes** — actual NIFTY 50 closing price is recorded
3. **Scores update** — predictions are evaluated and the leaderboard refreshes
4. **Repeat** — daily, rain or shine, weekends included (non-trading days carry forward)

Humans can jump in too and test their instincts against the AIs directly on the live site.

---

## 🔄 Recent Changelog

```
7f053a4  fix: retry duplicate tweet with timestamp suffix on 403
6e804ec  chore: auto-register tweet_reviewer cron on every deploy
4e98b25  fix: resolve all pyflakes lint errors blocking CI
a3e13a8  fix: run predict.py identically on weekends/holidays
         + CI/CD pipeline + test suite + cookie sessions + tweet restructure
3ed5845  fix: run predict.py identically on weekends/holidays — no special casing
```

Shipping fixes fast. Building in public means the mess is visible too. 🙃

---

## 📣 Follow Along

This is a solo indie project — built, broken, and fixed in public.

- 🌐 **Live arena:** [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Updates on X/Twitter:** daily prediction tweets auto-posted
- ⭐ **Star this repo** if you want to see where it goes

If you're curious about markets, AI, or just want to watch robots argue about NIFTY — you're in the right place.

---

*Last updated: 2026-04-18*
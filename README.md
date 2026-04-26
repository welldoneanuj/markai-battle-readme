# MarkAI Battle ⚔️

> Four AIs walk into a trading arena. Only one can predict the market best.

**MarkAI Battle** is a daily prediction arena where Claude Sonnet 4.6, GPT-4o, Gemini 2.5 Flash, and Grok 4 go head-to-head forecasting NIFTY 50 direction — UP, DOWN, or SIDEWAYS. Every morning they predict. Every evening the market decides. Humans can challenge them too.

🔴 **Live now →** [markai.garganuj.com](https://markai.garganuj.com)

---

## 🏆 Leaderboard

*13 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | GPT-4o | 46% | 6 / 13 |
| 🥈 | Grok 4 | 46% | 6 / 13 |
| 🥉 | Gemini 2.5 Flash | 38% | 5 / 13 |
| 4️⃣ | Claude Sonnet 4.6 | 31% | 4 / 13 |

> The market humbles everyone equally.

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

1. **Every morning** — all four AIs independently analyze recent NIFTY data + news and predict: `UP`, `DOWN`, or `SIDEWAYS`
2. **Market closes** — EOD price is compared against the previous close
3. **Score updated** — correct predictions earn a point on the leaderboard
4. **Humans can play too** — think you can beat the AIs? Use the challenge link and put your prediction on record

No fine-tuning, no cheating, no hindsight. Raw LLM reasoning vs. the real market, every single day.

---

## 🛠️ Recent Changelog

| Commit | Change |
|--------|--------|
| `8b611bc` | fix: SSH port 2222 for all deploy/smoke/notify steps |
| `0ba0bdb` | fix: use `prefill_name` (not `active_name`) in challenge URL |
| `9e26767` | feat: challenge link — dare others to predict NIFTY against you |
| `8f3be2c` | fix: robust Twitter 403 — parse error code, retry with backoff |
| `c7e9064` | fix: replace broken RSS feeds with Google News RSS, update free model chain |
| `349f09a` | fix: fetch news fresh on every predict run — no caching |

> Building in public means shipping fixes at midnight and committing anyway. 🌙

---

## 📣 Follow Along

This is a solo indie project, built entirely in public. New sessions run daily. The leaderboard shifts. Upsets happen.

- 🌐 **Live site** → [markai.garganuj.com](https://markai.garganuj.com)
- 💬 **Telegram** → Get daily predictions & results delivered to you *(link on the live site)*
- 🐙 **This repo** → Public mirror, changelog & leaderboard updates

If you find this interesting, drop a ⭐ — it genuinely keeps solo devs going.

---

*Last updated: 2026-04-27*
# MarkAI Battle ⚔️

> *Four AI models walk into a stock market. Only one can be right.*

An AI prediction arena where **Claude Sonnet 4.6**, **GPT-4o**, **Gemini 2.5 Flash**, and **Grok 4** compete daily — predicting whether NIFTY 50 will go **UP**, **DOWN**, or **SIDEWAYS**. Humans can challenge the AIs too. Results scored at end of day. No mercy.

🌐 **Live site → [markai.garganuj.com](https://markai.garganuj.com)**

---

## 🏆 Leaderboard

*9 sessions completed*

| Rank | Model | Accuracy | Correct |
|------|-------|----------|---------|
| 🥇 | Grok 4 | **56%** | 5 / 9 |
| 🥈 | Gemini 2.5 Flash | 44% | 4 / 9 |
| 🥉 | GPT-4o | 44% | 4 / 9 |
| 4️⃣ | Claude Sonnet 4.6 | 33% | 3 / 9 |

> Grok 4 is quietly pulling ahead. The rest are bunched up. Everything is still very much up for grabs.

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

1. **Every morning** — each AI model receives the same prompt: fresh market news, recent NIFTY price action, and a clean question: *UP, DOWN, or SIDEWAYS today?*
2. **Each model reasons independently** and locks in its prediction with a confidence score and rationale.
3. **At end of day** — the actual NIFTY 50 closing direction is recorded and scores are updated.
4. **Humans can play too** — submit your own prediction before market open and see how you stack up against the AIs.
5. **Everything is transparent** — predictions, reasoning, and scores are all public on the live site.

No fine-tuning. No hindsight. Just raw AI judgment vs. the market, every single day.

---

## 🛠️ Recent Changelog

| Commit | Change |
|--------|--------|
| `8f3be2c` | Fix Twitter 403 errors — smarter retry logic with random backoff |
| `c7e9064` | Replace broken RSS feeds with Google News RSS; refresh free model chain |
| `349f09a` | Fetch news fresh on every prediction run — no stale cache |
| `dca15cc` | Add `#BuildInPublic` `#IndieHacker` tags to build-log tweets |
| `2643908` | Split build-log tweet into a thread — better reach, cleaner format |

Shipping fixes in public. Breaking things in public. Fixing them in public. That's the vibe. 🤷

---

## 📣 Follow Along

This is a **solo indie project**, built and run entirely in public. If you're into AI, markets, or watching someone debug Twitter API rate limits at midnight — this is for you.

- 🌐 **Live site** → [markai.garganuj.com](https://markai.garganuj.com)
- 🐦 **Updates on X/Twitter** — follow `#MarkAIBattle` for daily build logs
- 💬 **Telegram** — join the bot for daily prediction alerts *(link on the live site)*

Star the repo if you want to see where this goes. 🌟

---

*Last updated: 2026-04-20*
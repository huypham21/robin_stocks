# PUSH Strategy Investing Plan

Huy’s preference sheet for the Robinhood MCP account (`••••1725`, options L3).  
Snapshot: ~8:50 PM CT, Tue Nov 3, 2026. **Not financial advice.**

One cash-secured put (CSP) reserves **strike × 100** in buying power.

---

## Account snapshot

| Metric | Value |
| --- | --- |
| Account value | ~$4,020 |
| Cash | ~$4,104 |
| Buying power | ~$54 |
| Open short puts | 3 (SOFI, LYFT, RIVN) |
| Equity sleeve | VOO ~0.019 sh (SOFI PUSH) |

Cash is mostly locked as collateral (~$4,050). Need ~**$1,200+** free BP (or a closed CSP) before the next contract.

---

## Core rules (preferences)

| Rule | Preference |
| --- | --- |
| Strategy | **PUSH**: sell CSP → keep credit → deploy **≥50%** of premium into equities |
| Tenor | **~30 DTE** (weeklies such as Dec 4 when in that window) |
| Premium target | **1.5–2%** of collateral per month (`credit ÷ strike`); up to ~3–5% OK when IV is rich and delta stays about **−0.15 to −0.25** |
| Strike style | OTM puts you would **own if assigned**; prefer POP ~**70–85%** |
| PUSH destination | **VOO** fractional (default ballast) |
| PUSH timing | Same day as CSP fill when possible (regular-hours market buy by dollar amount) |
| Auto-VOO | Authorized for **SOFI** fills; **LYFT / RIVN** need an explicit go-ahead |
| Execution | Trade only MCP `••••1725`. **Preview first**; place only on explicit confirmation |

Source playbook: YouTube PUSH video (`youtu.be/dZi8Vafw6TA`).

---

## Name selection preferences

### Prefer (SOFI-like underwrites)

- Stock roughly **$12–$28** (screener universe **$10–$40**)
- Collateral about **$1.1k–$1.6k** per contract when possible
- Liquid put markets; market cap **≥ $2B**; solid average volume
- Names you are willing to hold **100 shares** of if assigned

### Avoid / defer

- **Skip till after earnings** — do not open a new CSP if earnings fall before expiration; re-quote after the report
- Deprioritize **crypto-miners** (RIOT, WULF, IREN, CORZ, APLD, BMNR, GLXY, etc.) — poor “own if assigned” fit despite high IV
- Do not stack another short put on an underlying already open (**SOFI / LYFT / RIVN** while live)
- Wide-spread / illiquid names (e.g. video-style IOT) are not first trades

---

## Open positions

| Position | Strike | Expiry | Credit kept | Collateral | PUSH status |
| --- | ---: | --- | ---: | ---: | --- |
| SOFI short put ×1 | $14.50 | Dec 4, 2026 | $26 | $1,450 | Done — $13 VOO (~0.019 sh) |
| LYFT short put ×1 | $14.50 | Dec 4, 2026 | $44 | $1,450 | Pending explicit OK (~$22) |
| RIVN short put ×1 | $11.50 | Dec 4, 2026 | $27 | $1,150 | Pending explicit OK (~$13.50) |
| VOO long | — | — | — | ~$13 cost | SOFI PUSH filled |

---

## Daily CSP screener

Legend scan: **PUSH Daily CSP ($10–40)**  
Weekday timer: ~**9:30 AM CT** — re-runs the scan and suggests entries (does not place).

| Filter | Setting |
| --- | --- |
| Asset type | Stock |
| Last price | $10 – $40 |
| Market cap | ≥ $2B |
| Avg volume (30d) | ≥ 1M |
| Implied vol | ≥ 35% |
| Avg put volume (10d) | ≥ 2,000 |
| Put open interest | ≥ 5,000 |

**Ranking bias:** prefer $12–$28 ownable names → check earnings → quote ~30 DTE OTM puts in the 1.5–2% yield band → suggest. Never place without “preview” / “place”.

---

## Operating checklist

1. **Screen** — Run the daily scan (or wait for the weekday timer). Shortlist SOFI-like names; drop earnings conflicts and miner-heavy IV traps.
2. **Size** — Confirm free buying power ≥ strike × 100. If not, fund MCP or close / expire an existing CSP first.
3. **Preview → place** — Ask for a preview of one contract. Place only after an explicit “place it / place [ticker]”.
4. **PUSH** — On fill, deploy ≥50% of credit to VOO when authorized for that underlying (SOFI already on). Leave the rest as buffer.
5. **Manage** — Journal through expiration. On assignment, own the shares or roll with a new preview — no silent rolls.

---

## Risk reminder

Short puts can assign 100 shares on a gap-down. Premium does not offset large declines. Size so one assignment is uncomfortable, not catastrophic. This document is a preference sheet, not a guarantee of profit.

---

## Glossary

| Term | Meaning |
| --- | --- |
| **CSP** | Cash-secured put — short put with cash reserved to buy 100 shares at the strike |
| **DTE** | Days to expiration |
| **OTM** | Out of the money — put strike below the current stock price |
| **POP** | Probability of profit — model estimate the short put expires worthless / you keep the credit |
| **PUSH** | Deploy ≥50% of option premium into equities (here: VOO) |
| **Skip till after** | Wait until earnings are reported before selling a put that expires after that report |

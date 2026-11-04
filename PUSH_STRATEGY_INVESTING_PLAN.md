# PUSH Strategy Investing Plan

Huy’s preference sheet for the Robinhood MCP account (`••••1725`, options L3).  
Updated: ~5:47 AM CT, Wed Nov 4, 2026. **Not financial advice.**

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
| Tenor | **~30 DTE** entry (weeklies such as Dec 4 when in that window) |
| Premium target | **1.5–2%** of collateral per month (`credit ÷ strike`); up to ~3–5% OK when IV is rich and delta stays about **−0.15 to −0.25** |
| Strike style | OTM puts you would **own if assigned**; prefer POP ~**70–85%** |
| **Profit take** | **Buy to close at 50% of credit** — GTC limit BTC placed **immediately after CSP fill** |
| **21 DTE** | If not yet at 50% profit by **21 DTE** → **close or roll** (credit only) |
| **Defense** | Put mark **≥ 2× credit** OR stock **closes below strike** → review: **roll out** (and **down** if possible) for a **net credit**, or **accept assignment only if** post-assignment shares are **≤ 35% of account**. **No debit rolls** |
| PUSH destination | **VOO** fractional (default ballast) |
| PUSH timing | Same day as CSP fill when possible (regular-hours market buy by dollar amount) |
| Auto-VOO | Authorized for **SOFI** fills; **LYFT / RIVN** need an explicit go-ahead |
| Execution | Trade only MCP `••••1725`. New CSP opens: **preview → place** on confirmation. Standing management (50% BTC, 21 DTE, defense) **executes per these rules** |

Source playbook: YouTube PUSH video (`youtu.be/dZi8Vafw6TA`).

---

## Position management (strict)

1. **50% profit take** — Right after a short put fills, place a **GTC buy-to-close** limit at **50% of the credit** received (per-share). Example: sold @ $0.26 → BTC @ $0.13.
2. **21 DTE checkpoint** — If the 50% BTC has not filled by **21 DTE**, **close** the put or **roll** to a later expiry (strike down if possible) for a **net credit**.
3. **Defense trigger** — If the put’s price reaches **2× the original credit**, or the **stock closes below the strike**, run a review:
   - Prefer **roll out** (and **down** if possible) for a **net credit**.
   - **Accept assignment** only if 100 shares × strike would be **≤ 35% of account value**.
   - **Never roll for a debit.**

---

## Name selection preferences

### Prefer (SOFI-like underwrites)

- Stock roughly **$12–$28** (screener universe **$10–$40**)
- Collateral about **$1.1k–$1.6k** per contract when possible
- Liquid put markets; market cap **≥ $2B**; solid average volume
- Names you are willing to hold **100 shares** of if assigned (subject to ≤35% account rule)

### Avoid / defer

- **Skip till after earnings** — do not open a new CSP if earnings fall before expiration; re-quote after the report
- Deprioritize **crypto-miners** (RIOT, WULF, IREN, CORZ, APLD, BMNR, GLXY, etc.) — poor “own if assigned” fit despite high IV
- Do not stack another short put on an underlying already open (**SOFI / LYFT / RIVN** while live)
- Wide-spread / illiquid names (e.g. video-style IOT) are not first trades

---

## Open positions + 50% BTC targets

| Position | Credit | 50% BTC limit | Expiry | Collateral | PUSH status |
| --- | ---: | ---: | --- | ---: | --- |
| SOFI $14.50 put ×1 | $0.26 | **$0.13 GTC** | Dec 4, 2026 | $1,450 | Done — $13 VOO (~0.019 sh) |
| LYFT $14.50 put ×1 | $0.44 | **$0.22 GTC** | Dec 4, 2026 | $1,450 | Pending explicit OK (~$22) |
| RIVN $11.50 put ×1 | $0.27 | **$0.14 GTC** | Dec 4, 2026 | $1,150 | Pending explicit OK (~$13.50) |
| VOO long | — | — | — | ~$13 cost | SOFI PUSH filled |

Dec 4 from Nov 4 ≈ **30 DTE** → **21 DTE checkpoint ≈ Nov 13**.

---

## Daily CSP screener

Legend scan: **PUSH Daily CSP ($10–40)**  
Weekday timers: ~**9:30 AM CT** (suggestions) and a management check (50% / 21 DTE / defense).

| Filter | Setting |
| --- | --- |
| Asset type | Stock |
| Last price | $10 – $40 |
| Market cap | ≥ $2B |
| Avg volume (30d) | ≥ 1M |
| Implied vol | ≥ 35% |
| Avg put volume (10d) | ≥ 2,000 |
| Put open interest | ≥ 5,000 |

**Ranking bias:** prefer $12–$28 ownable names → check earnings → quote ~30 DTE OTM puts in the 1.5–2% yield band → suggest. Never place a **new CSP** without “preview” / “place”.

---

## Operating checklist

1. **Screen → size → preview → place** — SOFI-like names only; drop earnings conflicts. Confirm BP ≥ strike × 100. Place CSP only after explicit confirmation.
2. **On CSP fill** — Immediately place GTC BTC at 50% of credit. PUSH ≥50% of credit to VOO when authorized for that name.
3. **Manage to 21 DTE** — Let the 50% BTC work. At 21 DTE if still open: close or roll out for a net credit (down in strike if possible). No debit rolls.
4. **Defense** — If put ≥ 2× credit or stock closes below strike: run a roll/assign review. Assignment only if 100 shares would be ≤ 35% of account value.

---

## Risk reminder

Short puts can assign 100 shares on a gap-down. Premium does not offset large declines. The **35% account cap** is a hard ceiling on intentional assignment — not a profit guarantee.

---

## Glossary

| Term | Meaning |
| --- | --- |
| **CSP** | Cash-secured put — short put with cash reserved to buy 100 shares at the strike |
| **DTE** | Days to expiration |
| **OTM** | Out of the money — put strike below the current stock price |
| **POP** | Probability of profit — model estimate the short put expires worthless / you keep the credit |
| **PUSH** | Deploy ≥50% of option premium into equities (here: VOO) |
| **BTC** | Buy to close — close a short option |
| **50% of credit** | Buy-back price = half the premium originally received |
| **Skip till after** | Wait until earnings are reported before selling a put that expires after that report |

# AEGIENT_STATE.md

**Owner:** Chris Falck / Aegient Ltd
**Last updated:** 2026-04-27 — initial creation
**Purpose:** State document for the Aegient Ltd corporate web presence. Read by Claude at the start of any session involving the aegient repo.

---

## 1. What This Repo Is

`aegient` is the corporate web presence for Aegient Ltd, the legal entity behind the Quiet product suite. It is a static site hosted on Cloudflare Pages, deployed from the `tickbox-smc/aegient` GitHub repository.

The site publishes publicly verifiable company information: registration number, registered address, product operator statement, and contact address. It is not a marketing site — that role belongs to `getquiet.co.uk`.

**Domain:** `aegient.com`
**Hosting:** Cloudflare Pages — connected to `tickbox-smc/aegient`
**Local path:** `/Users/chrisfalck/aegient`

---

## 2. Current State

### 2.1 Files

| File | Purpose |
|---|---|
| `index.html` | Single-page company registration card. All content inline. |
| `wrangler.jsonc` | Cloudflare Pages configuration. |
| `README.md` | Minimal repo readme. |

### 2.2 Published Content

The current page displays:

- **Registered company:** England and Wales — No. 17154349
- **Registered address:** 3a Park Avenue, Lytham St Annes, Lancashire FY8 5QU
- **Product:** Operator of getquiet.co.uk
- **Contact:** hello@aegient.com

### 2.3 Design Alignment

`index.html` uses the same core design tokens as `getquiet/DESIGN.md`:

| Token | Value |
|---|---|
| `--teal` | `#1d9e75` |
| `--bg-tertiary` | `#eeece7` |
| `--bg-primary` | `#ffffff` |
| `--text-primary` | `#2c2c2a` |
| `--text-secondary` | `#5f5e5a` |
| `--text-tertiary` | `#888780` |
| `--border-subtle` | `rgba(44, 44, 42, 0.12)` |
| `--radius-lg` | `12px` |

**Rule:** If core token values change in `getquiet/DESIGN.md`, review `aegient/index.html` for alignment before publishing.

---

## 3. What Is Not Here

The following are intentionally absent from this repo:

- Product marketing copy — lives in `getquiet/`
- Privacy notice — lives in `getquiet/` (quiet_privacy_notice.md / published page)
- Financial or commercial information
- Any dynamic functionality — this is a static informational page only

---

## 4. Future Scope

Items identified for future addition as the company develops. None are scheduled.

| Item | Notes |
|---|---|
| Privacy policy link | Link to the published privacy notice at getquiet.co.uk when it goes live. |
| Directors / team page | Optional — only if needed for investor or regulatory purposes. |
| Additional products | If Aegient operates more than one product, the product operator statement will need updating. |
| GDPR / ICO registration notice | If ICO registration number is issued, publish it here alongside the company reg. |

---

## 5. Decisions Log

| Date | Decision | Notes |
|---|---|---|
| 2026-04-27 | Lightweight state document adopted | Aegient repo is simple enough that a full QUIET_STATE.md-scale document is not warranted. This document covers what Claude needs to reason about the repo in planning sessions. |

---

*Aegient Ltd — internal reference document*

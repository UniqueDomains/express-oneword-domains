# Available .EXPRESS One-Word Domains (11,861)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C861%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .express one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,861 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,861 domains · **Median ask:** $19.99 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/express`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/express?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./express.csv">CSV</a> / <a href="./express.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .EXPRESS search](https://unique.domains/domains/tld/express?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .EXPRESS search](https://unique.domains/domains/tld/express?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .EXPRESS one-word domain catalog.

### Files

- `express.csv`, public CSV extract (1,000 rows)
- `express.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/express-oneword-domains/main/express.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| avon.express | available | $16.99    | —             | high           | low    | 4      | name.com                                                  |
| any.express  | resell    | —         | —             | high           | medium | 3      | Global Domains International, Inc. DBA DomainCostClub.com |
| act.express  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                                  |
| away.express | available | $16.99    | —             | high           | low    | 4      | name.com                                                  |
| cool.express | resell    | —         | —             | high           | low    | 4      | Automattic Inc.                                           |
| ala.express  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                                  |
| both.express | available | $16.99    | —             | high           | low    | 4      | name.com                                                  |
| data.express | resell    | —         | —             | high           | medium | 4      | Porkbun LLC                                               |
| ana.express  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                                  |
| busy.express | available | $16.99    | —             | high           | low    | 4      | name.com                                                  |
| door.express | resell    | —         | —             | high           | low    | 4      | Squarespace Domains II LLC                                |
| bag.express  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                                  |
| cane.express | available | $16.99    | —             | medium         | low    | 4      | name.com                                                  |
| farm.express | resell    | —         | —             | high           | low    | 4      | Sav.com, LLC - 1                                          |
| beg.express  | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo                                                  |
| cent.express | available | $16.99    | —             | high           | low    | 4      | name.com                                                  |
| lock.express | resell    | —         | —             | medium         | low    | 4      | Squarespace Domains II LLC                                |
| bud.express  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo                                                  |
| chew.express | available | $16.99    | —             | medium         | low    | 4      | name.com                                                  |
| love.express | resell    | —         | —             | high           | medium | 4      | Spaceship, Inc.                                           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,861 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/express?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/express?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers one-word .express domain names spanning many naming styles, from short action phrases like dogsit and toneup to established terms like sports and design. Median asking price across the set sits near $20, putting most names within reach for direct purchase rather than negotiation. The mix ranges from clearly brandable, founder-ready names to broader terms worth comparing on price and clarity before buying.

- 11,861 one-word .express domains available across many styles
- Median asking price near $20 — accessible for most budgets
- Brandable names like dogsit, letitbe, and toneup ready to own
- Updated daily so pricing and inventory stay current

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .EXPRESS One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .EXPRESS page](https://unique.domains/domains/tld/express?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

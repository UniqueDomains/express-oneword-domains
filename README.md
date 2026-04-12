# Available .EXPRESS One-Word Domains (8,946)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-8%2C949%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C946%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .express one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 8,949 rows · **Live catalog:** 8,946 domains

**Last updated:** 2026-04-12  
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

- `express.csv` — public CSV extract (8,949 rows)
- `express.json` — public JSON extract (8,949 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/express-oneword-domains/main/express.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| genius.express     | available | $16.99    | $50.99        | 98             | 45     | 6      | name.com                                                  |
| wise.express       | resell    | —         | —             | 98             | 72     | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| aaa.express        | premium   | $42.90    | $42.90        | 70             | 42     | 3      | namecheap                                                 |
| nest.express       | available | $16.99    | —             | 74             | 41     | 4      | name.com                                                  |
| get.express        | resell    | —         | —             | 88             | 69     | 3      | Sav.com, LLC - 27                                         |
| water.express      | premium   | $42.90    | $42.90        | 108            | 40     | 5      | namecheap                                                 |
| unity.express      | available | $16.99    | $50.99        | 70             | 40     | 5      | name.com                                                  |
| prompt.express     | resell    | —         | —             | 114            | 68     | 6      | Sav.com, LLC - 13                                         |
| direct.express     | premium   | $123.75   | $123.75       | 104            | 39     | 6      | name.com                                                  |
| shared.express     | available | $16.99    | $50.99        | 70             | 39     | 6      | name.com                                                  |
| news.express       | resell    | —         | —             | 100            | 64     | 4      | Spaceship, Inc.                                           |
| use.express        | premium   | $42.90    | $42.90        | 78             | 37     | 3      | namecheap                                                 |
| conscious.express  | available | $16.99    | $50.99        | 89             | 38     | 9      | name.com                                                  |
| domain.express     | resell    | —         | —             | 80             | 64     | 6      | Porkbun LLC                                               |
| diamond.express    | premium   | $42.90    | $42.90        | 76             | 36     | 7      | namecheap                                                 |
| risk.express       | available | $49.98    | —             | 62             | 38     | 4      | namecheap                                                 |
| sense.express      | resell    | —         | —             | 102            | 63     | 5      | Porkbun LLC                                               |
| technology.express | premium   | $128.70   | $128.70       | 88             | 35     | 10     | namecheap                                                 |
| sharp.express      | available | $16.99    | $50.99        | 84             | 36     | 5      | name.com                                                  |
| fun.express        | resell    | —         | —             | 122            | 62     | 3      | OVH SAS                                                   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 8,949-row public sample | 8,946 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/express?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/express?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .EXPRESS One-Word Domains*. Version 2026-04-12. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .EXPRESS page](https://unique.domains/domains/tld/express?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_express_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

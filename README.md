# Available .CLICK One-Word Domains (19,929)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-19%2C929%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .click one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **19,929 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 19,929 domains · **Median ask:** $49.08 · **High-demand under $2,500:** 25

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/click`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/click?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./click.csv">CSV</a> / <a href="./click.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CLICK search](https://unique.domains/domains/tld/click?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CLICK search](https://unique.domains/domains/tld/click?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CLICK one-word domain catalog.

### Files

- `click.csv`, public CSV extract (1,000 rows)
- `click.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/click-oneword-domains/main/click.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| economy.click   | premium   | $91       | $130          | high           | low    | 7      | namecheap       |
| ten.click       | premium   | $116      | $116          | high           | low    | 3      | namesilo        |
| scotch.click    | premium   | $116      | $116          | high           | low    | 6      | namesilo        |
| computer.click  | premium   | $116      | $116          | high           | medium | 8      | namesilo        |
| sage.click      | premium   | $116      | $116          | high           | medium | 4      | namesilo        |
| allied.click    | available | $2.19     | $12.99        | high           | low    | 6      | namesilo        |
| set.click       | resell    | —         | —             | high           | low    | 3      | Dynadot, LLC    |
| some.click      | premium   | $116      | $116          | high           | low    | 4      | namesilo        |
| inviting.click  | available | $2.19     | $12.99        | high           | low    | 8      | namesilo        |
| exemplary.click | available | $1.80     | $17.98        | high           | low    | 9      | namecheap       |
| cozy.click      | premium   | $91       | $130          | high           | low    | 4      | namecheap       |
| plastic.click   | resell    | $1.99     | —             | high           | low    | 7      | name.com        |
| built.click     | premium   | $116      | $116          | high           | low    | 5      | namesilo        |
| tracks.click    | premium   | $116      | $116          | high           | low    | 6      | namesilo        |
| kahn.click      | available | $2.19     | $12.99        | high           | low    | 4      | namesilo        |
| acc.click       | premium   | $116      | $116          | high           | low    | 3      | namesilo        |
| ucla.click      | available | $1.80     | $17.98        | high           | low    | 4      | namecheap       |
| adz.click       | premium   | $116      | $116          | medium         | low    | 3      | namesilo        |
| bigos.click     | available | $2.19     | $12.99        | medium         | low    | 5      | namesilo        |
| cafe.click      | resell    | —         | —             | high           | low    | 4      | Spaceship, Inc. |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 19,929 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 25 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/click?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/click?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=related_pricing)

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
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection covers 10,817 one-word and short-phrase .click domain names, with a median asking price near $45. The mix ranges from plain everyday words like girls.click and gingerbread.click to compact phrases such as dogsit.click and keepfit.click, plus brand-style entries like Snickers.click. Because .click is an open, low-barrier TLD, the pool is large and varied in tone, length, and word type. When comparing these domains, weigh the asking price against likely renewal cost, check for trademark overlap on brand-style words, and judge how easily each name reads aloud before shortlisting it for a project or portfolio.

- 10,817 one-word .click domains, median ask near $45
- Mix of everyday words, verbs, and brand-style names
- Includes names like Snickers.click and dogsit.click
- Updated daily for fresh pricing and selection

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CLICK One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CLICK page](https://unique.domains/domains/tld/click?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_click_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`

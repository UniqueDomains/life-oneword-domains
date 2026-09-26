# Available .LIFE One-Word Domains (16,859)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C859%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .life one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,859 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,859 domains · **Median ask:** $4.99 · **High-demand under $2,500:** 0

**Last updated:** 2026-09-26
**Canonical page:** `https://unique.domains/domains/tld/life`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/life?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./life.csv">CSV</a> / <a href="./life.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .LIFE search](https://unique.domains/domains/tld/life?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .LIFE search](https://unique.domains/domains/tld/life?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .LIFE one-word domain catalog.

### Files

- `life.csv`, public CSV extract (1,000 rows)
- `life.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/life-oneword-domains/main/life.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar    |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------ |
| acyl.life   | available | $2.98     | $46.48        | medium         | low    | 4      | namecheap    |
| sink.life   | resell    | $2.99     | —             | high           | low    | 4      | Sav.com, LLC |
| fig.life    | premium   | $46.20    | $92.40        | high           | low    | 3      | namecheap    |
| bleb.life   | available | $2.98     | $46.48        | medium         | low    | 4      | namecheap    |
| api.life    | resell    | —         | —             | high           | medium | 3      | DNSPod, Inc. |
| hid.life    | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo     |
| jeer.life   | available | $2.98     | $46.48        | medium         | low    | 4      | namecheap    |
| bpi.life    | resell    | —         | —             | high           | low    | 3      | Sav.com, LLC |
| nay.life    | premium   | $42.90    | $85.80        | medium         | low    | 3      | namecheap    |
| mown.life   | available | $2.98     | $46.48        | medium         | low    | 4      | namecheap    |
| diy.life    | resell    | —         | —             | high           | low    | 3      | Dynadot Inc  |
| czech.life  | premium   | $82.50    | $82.50        | high           | low    | 5      | name.com     |
| spat.life   | available | $3.49     | $35.99        | high           | low    | 4      | namesilo     |
| fla.life    | resell    | —         | —             | high           | low    | 3      | DNSPod, Inc. |
| iraqi.life  | premium   | $64.35    | $128.70       | high           | low    | 5      | namecheap    |
| tout.life   | available | $2.98     | $46.48        | high           | low    | 4      | namecheap    |
| fog.life    | resell    | —         | —             | high           | low    | 3      | DNSPod, Inc. |
| munich.life | premium   | $46.20    | $92.40        | high           | low    | 6      | namecheap    |
| xliv.life   | available | $2.98     | $46.48        | medium         | low    | 4      | namecheap    |
| guy.life    | resell    | —         | —             | high           | low    | 3      | —            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,859 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/life?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/life?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=related_pricing)

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

This list covers 9,499 one-word domain names registered under the .life extension, ranging from simple everyday words like “okay” and “feel” to compound terms like “bedframe” and “getlife.” With a median asking price near $5, most names in this set are accessible for early-stage evaluation before committing to renewal costs. .life domains suit personal, wellness, and lifestyle-oriented projects, making them a practical starting point for founders seeking a short, memorable name and investors scanning for low-cost entry points across a large TLD pool.

- 9,499 one-word .life domains available for evaluation
- Median asking price near $5 across this selection
- Mix of short, brandable terms and compound one-word names
- Updated daily to reflect current .life domain pricing

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

> Unique Domains. *Available .LIFE One-Word Domains*. Version 2026-09-26. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .LIFE page](https://unique.domains/domains/tld/life?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_life_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`

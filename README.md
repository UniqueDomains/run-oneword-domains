# Available .RUN One-Word Domains (15,370)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C370%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .run one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,370 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,370 domains · **Median ask:** $6.01 · **High-demand under $2,500:** 1

**Last updated:** 2026-08-20
**Canonical page:** `https://unique.domains/domains/tld/run`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/run?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./run.csv">CSV</a> / <a href="./run.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .RUN search](https://unique.domains/domains/tld/run?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .RUN search](https://unique.domains/domains/tld/run?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .RUN one-word domain catalog.

### Files

- `run.csv`, public CSV extract (1,000 rows)
- `run.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/run-oneword-domains/main/run.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain   | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| -------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| agog.run | available | $3.48     | $35.98        | low            | low    | 4      | namecheap                                    |
| old.run  | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC                             |
| abo.run  | premium   | $13       | $26           | low            | low    | 3      | namecheap                                    |
| area.run | available | $6.99     | —             | high           | low    | 4      | name.com                                     |
| van.run  | resell    | —         | —             | high           | low    | 3      | Spaceship, Inc.                              |
| awe.run  | premium   | $14       | $28           | high           | low    | 3      | namecheap                                    |
| aunt.run | available | $6.99     | —             | high           | low    | 4      | name.com                                     |
| bake.run | resell    | —         | —             | high           | low    | 4      | Sav.com, LLC - 48                            |
| beg.run  | premium   | $14       | $28           | medium         | low    | 3      | namecheap                                    |
| awol.run | available | $3.48     | $35.98        | low            | low    | 4      | namecheap                                    |
| ball.run | resell    | —         | —             | medium         | low    | 4      | Xin Net Technology Corporation               |
| dig.run  | premium   | $13       | $26           | high           | low    | 3      | namecheap                                    |
| bats.run | available | $3.48     | $35.98        | low            | low    | 4      | namecheap                                    |
| bash.run | resell    | —         | —             | high           | low    | 4      | NameCheap, Inc.                              |
| due.run  | premium   | $14       | $28           | high           | low    | 3      | namecheap                                    |
| born.run | available | $6.99     | —             | high           | low    | 4      | name.com                                     |
| beat.run | resell    | —         | —             | high           | low    | 4      | Xin Net Technology Corporation               |
| hat.run  | premium   | $14       | $28           | high           | low    | 3      | namecheap                                    |
| bury.run | available | $6.99     | —             | medium         | low    | 4      | name.com                                     |
| duck.run | resell    | —         | —             | medium         | low    | 4      | Xiamen ChinaSource Internet Service Co., Ltd |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,370 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/run?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/run?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=related_pricing)

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

This list covers one-word .run domain names built from everyday phrases and action words — think getlucky.run, settledown.run, and jetblack.run. The .run extension naturally fits movement, habit, and lifestyle branding, which shows up across the set in names tied to routines, food, and daily activity. With a median ask near $8, most names in this selection are priced for fast comparison rather than long negotiation. Whether you're scanning for a quick pickup or a brandable name to build on, the value here comes from volume: thousands of short, memorable .run strings updated daily.

- 10,683 one-word .run domain names in this selection
- Median ask near $8 across the set
- Lifestyle, habit, and action-word naming patterns
- Updated daily to reflect current .run domain pricing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RUN One-Word Domains*. Version 2026-08-20. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RUN page](https://unique.domains/domains/tld/run?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

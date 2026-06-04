# Available .RUN One-Word Domains (10,683)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C683%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .run one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,683 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,683 domains · **Median ask:** $8.04 · **High-demand under $2,500:** 0

**Last updated:** 2026-06-04  
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

- `run.csv` — public CSV extract (1,000 rows)
- `run.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/run-oneword-domains/main/run.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                           |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------- |
| person.run     | premium   | —         | —             | 80             | 13     | 6      | —                                                   |
| king.run       | resell    | —         | —             | 97             | 44     | 4      | Chengdu West Dimension Digital Technology Co., Ltd. |
| mom.run        | premium   | —         | —             | 86             | 27     | 3      | —                                                   |
| erase.run      | available | $6.99     | —             | 86             | 10     | 5      | name.com                                            |
| striking.run   | available | $6.99     | —             | 89             | 9      | 8      | name.com                                            |
| touching.run   | premium   | —         | —             | 88             | 5      | 8      | —                                                   |
| Iam.run        | premium   | —         | —             | 100            | 45     | 4      | —                                                   |
| loved.run      | available | $6.99     | —             | 80             | 16     | 5      | name.com                                            |
| historical.run | available | $6.99     | $41.99        | 88             | 13     | 10     | name.com                                            |
| pope.run       | available | $6.99     | —             | 80             | 20     | 4      | name.com                                            |
| pepsicola.run  | available | $6.99     | —             | 82             | 6      | 10     | name.com                                            |
| leaf.run       | resell    | —         | —             | 92             | 32     | 4      | Dynadot Inc                                         |
| portable.run   | premium   | —         | —             | 84             | 12     | 8      | —                                                   |
| recommend.run  | available | $6.99     | —             | 96             | 19     | 9      | name.com                                            |
| power.run      | premium   | —         | —             | 98             | 28     | 5      | —                                                   |
| phrase.run     | available | $6.99     | —             | 94             | 11     | 6      | name.com                                            |
| tradition.run  | available | $6.99     | —             | 88             | 14     | 9      | name.com                                            |
| ranking.run    | resell    | —         | —             | 94             | 22     | 7      | Sav.com, LLC - 39                                   |
| sensitive.run  | available | $6.99     | —             | 84             | 10     | 9      | name.com                                            |
| nought.run     | available | $6.99     | $41.99        | 92             | 6      | 6      | name.com                                            |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,683 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/run?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/run?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of .run domains, a niche extension that naturally fits motion, fitness, events, software tasks, and action-oriented brands. The examples show a broad mix: first names like Liam.run, verbs and commands like gearup.run, utility terms like popup.run, and quirky dictionary words like edamame.run. With a median ask of 9.00, the main question is less entry price and more fit. When comparing these domains, focus on whether the word becomes clearer or stronger with .run attached, whether it is easy to say and type, and whether the term could create trademark friction if used commercially.

- Prioritize words that pair naturally with .run
- Check spelling clarity and spoken recall
- Low ask helps, but fit matters more than price
- Avoid terms with obvious trademark exposure

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .RUN One-Word Domains*. Version 2026-06-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .RUN page](https://unique.domains/domains/tld/run?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_run_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

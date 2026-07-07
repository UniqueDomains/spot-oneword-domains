# Available .SPOT One-Word Domains (12,847)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C847%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .spot one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,847 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,847 domains · **Median ask:** $258.50 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/spot`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/spot?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./spot.csv">CSV</a> / <a href="./spot.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SPOT search](https://unique.domains/domains/tld/spot?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SPOT search](https://unique.domains/domains/tld/spot?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SPOT one-word domain catalog.

### Files

- `spot.csv`, public CSV extract (1,000 rows)
- `spot.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/spot-oneword-domains/main/spot.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| ahuh.spot | available | $25.99    | $25.99        | high           | low    | 4      | namesilo  |
| abc.spot  | premium   | $3,250    | $3,250        | high           | medium | 3      | namecheap |
| atop.spot | available | $25.99    | $25.99        | medium         | low    | 4      | namesilo  |
| aid.spot  | premium   | $3,125    | —             | medium         | low    | 3      | name.com  |
| chop.spot | available | $25.99    | $25.99        | medium         | low    | 4      | namesilo  |
| ala.spot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| clue.spot | available | $31.98    | —             | high           | low    | 4      | namecheap |
| axe.spot  | premium   | $1,107    | $1,107        | medium         | low    | 3      | namesilo  |
| jock.spot | available | $25.99    | $25.99        | high           | low    | 4      | namesilo  |
| BJP.spot  | premium   | $1,250    | —             | medium         | low    | 3      | name.com  |
| Jody.spot | available | $31.98    | —             | high           | low    | 4      | namecheap |
| CNN.spot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| lust.spot | available | $25.99    | $25.99        | high           | low    | 4      | namesilo  |
| dew.spot  | premium   | $1,107    | $1,107        | medium         | low    | 3      | namesilo  |
| pity.spot | available | $18.99    | $39.99        | high           | low    | 4      | name.com  |
| feb.spot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| pony.spot | available | $25.99    | $25.99        | high           | low    | 4      | namesilo  |
| fee.spot  | premium   | $3,125    | —             | high           | low    | 3      | name.com  |
| rake.spot | available | $25.99    | $25.99        | medium         | low    | 4      | namesilo  |
| gal.spot  | premium   | $1,107    | $1,107        | medium         | low    | 3      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,847 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/spot?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/spot?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=related_pricing)

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

This selection contains 12,847 one-word .spot domain names covering tech, lifestyle, food, and charity themes — from hightech.spot to comicrelief.spot. The median ask sits near $258, with naming styles ranging from short single words to recognizable compound phrases. Compare spelling simplicity, length, and thematic fit before deciding which of these .spot names best suits a brand or an early TLD position.

- 12,847 one-word .spot domain names, updated daily
- Median ask near $258 across this .spot selection
- Mix of brandable single words and compound phrases
- Themes span tech, lifestyle, food, and charity names

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SPOT One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SPOT page](https://unique.domains/domains/tld/spot?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_spot_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`

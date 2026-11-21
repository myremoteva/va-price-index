# Virtual assistant price index (open data)

Prices that virtual assistant providers publish on their own pricing pages, side by side, with the price per hour and the basis for each figure. Version 2026-11. Provider pages read on 28 October 2026. Next check due 28 November 2026.

Canonical page: https://myremoteva.com/va-price-index
DOI: https://doi.org/10.5281/zenodo.24424846 (Zenodo)
Kaggle mirror: https://www.kaggle.com/datasets/myremoteva/virtual-assistant-price-index-nov-2026

## Disclosure
Published by MyRemoteVA, which sells managed virtual assistant services and is one of the providers in the table. We record only what each provider shows on its own public pricing page and say when a figure is our own arithmetic.

## Files
| File | What it holds |
|---|---|
| `va-price-index.csv` | One row per published plan: provider, plan, billing, hours, price in USD, USD per hour, basis, commitment, location, source URL, date read |
| `va-price-index.json` | The same rows plus metadata, notes and how to cite |
| `myremoteva-hours-to-cost.csv` | The lowest MyRemoteVA monthly cost for 1 to 160 hours a month, from its published plans |

## Method
- Prices are read from each provider's public pricing page on the date shown. Nothing is estimated from reviews or third-party sites.
- `basis` says whether the hourly figure is stated on the page, or is our arithmetic (price divided by hours, with the assumption written in the column).
- Five providers are covered because those were the ones whose prices could be read on the date. It is not the whole market.
- Prices change. Check the provider's own page before you buy.

## Licence
CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Credit MyRemoteVA, link to https://myremoteva.com/va-price-index, and state the date the prices were read.

## Cite
MyRemoteVA, Virtual assistant price index, version 2026-11, https://myremoteva.com/va-price-index

## Corrections
If a provider's price has changed, email info@myremoteva.com with the page URL.

# Online therapy open data (OnlineTherapy.me)

Two open datasets from [OnlineTherapy.me](https://onlinetherapy.me), an independent comparison of US online therapy and psychiatry services. Every figure is read from a primary source and carries the date it was checked. Free to reuse under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): credit "OnlineTherapy.me" with a link to the page named for each dataset.

## 1. Online therapy session prices without insurance

`online-therapy-session-prices.csv`: what one session costs without insurance at the 22 US online therapy services that publish a per-session self-pay price, as each service's own page states it. One row per service, with the price as printed, the session price in dollars, the first-session price where it differs, session length, the date checked and the source page.

- Median starting price: $155 a session; range $40 to $275 (prices checked November 4, 2026).
- Analysis: [Online therapy pricing report](https://onlinetherapy.me/research/online-therapy-pricing)
- Citable version with a DOI: [10.5281/zenodo.23772949](https://doi.org/10.5281/zenodo.23772949)

## 2. Medicare psychotherapy rates by locality, 2026 and 2027

`medicare-psychotherapy-rates-2026-2027.csv`: what Medicare pays for each psychotherapy code (90791, 90832, 90834, 90837, 90846, 90847, 90853, 90839, 90840, 90785, 96127) in each of Medicare's 109 payment localities, for 2026 and for 2027 under CMS's final rule (CMS-1848-F), at the full rate, the 85% rate (psychiatric NPs and PAs) and the 75% rate (LCSWs, LMFTs and LPCs), plus the facility rate.

- Computed from CMS's physician fee schedule files (RVUs, GPCIs and each year's conversion factor) and checked against the payment amounts CMS publishes. National 90837 goes from $167.00 (2026) to $183.37 (2027), +9.8%.
- Lookup by state, locality and license: [Medicare therapy rates](https://onlinetherapy.me/for-therapists/medicare-rates)
- Citable version with a DOI: [10.5281/zenodo.24086523](https://doi.org/10.5281/zenodo.24086523)

## The full dataset

These are free samples of the OnlineTherapy.me online therapy market dataset (prices and plans, insurance plans named, prescribing policy, clinician pay at 25 platforms, operators and government actions, cancellation terms, discounts, employer benefits), re-checked monthly: [onlinetherapy.me/data](https://onlinetherapy.me/data).

Not medical, billing or legal advice. In a mental health crisis in the US, call or text 988.

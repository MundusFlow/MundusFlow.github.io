# Mundusflow Digital Tools

Live at [mundusflow.github.io](https://mundusflow.github.io/)

A static directory page linking out to every free Mundusflow calculator, grouped
by trade, plus a CTA banner for each paid CFO workbook. Plain HTML and CSS &mdash;
no build step, no backend.

## Sections

- **Auto Shop CFO** &mdash; links to the 5 calculators at [auto-shop-cfo](https://mundusflow.github.io/auto-shop-cfo/)
- **Electrician Business CFO** &mdash; links to the 5 calculators at [electrician-business-cfo](https://mundusflow.github.io/electrician-business-cfo/)
- **Freelance CFO** &mdash; links to the 2 calculators at [freelance-tax-runway-estimator](https://mundusflow.github.io/freelance-tax-runway-estimator/)

Each calculator link points to an anchor (e.g. `#quote-builder`) on the
corresponding niche site, which scrolls straight to that calculator's card.

## Deploying

This repo is the GitHub Pages *user site* for the `MundusFlow` account, so it
must be named exactly `MundusFlow.github.io` and serves from the `main` branch
at the root domain (Settings &rarr; Pages &rarr; deploy from `main`).

## Keeping it in sync

If a calculator is renamed, added, or removed on one of the niche sites, its
card `id` and the corresponding link here need to match.

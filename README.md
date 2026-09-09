# Coco Crochet — Shopify theme (YourPattern / Horizon)

Theme source for the Coco Crochet Shopify store. Migrated on 2026-09-09 from the
YourPattern storefront backup (`yourpattern-shopify-theme/develop`, backup of 2026-09-03).

## Theme

- Base theme: Horizon
- Imported version: 4.1.5
- Product focus: digital crochet patterns (PDF downloads)

## Custom storefront

- `sections/yp-hero.liquid`: crochet-focused homepage hero.
- `sections/yp-home-sections.liquid`: benefits, category grid, featured patterns, and learning links.
- `sections/yp-digital-pattern-notice.liquid`: product-page notice that the listing is a PDF pattern, not a physical item.
- `assets/yp-category-*`: category photography.

The homepage category grid expects these collection handles to exist in the store:
`animals-amigurumi-crochet-patterns`, `bags-accessories-crochet-patterns`,
`flowers-plants-crochet-patterns`, `home-decor-crochet-patterns`,
`seasonal-holiday-crochet-patterns`, `dolls-characters-crochet-patterns`.

## Workflow

This repo is connected to the store through the
[Shopify GitHub integration](https://shopify.dev/docs/storefronts/themes/tools/github).
Pushes to `main` sync automatically to the connected theme, and changes saved in the
Shopify theme editor are committed back to `main` by Shopify.

Before pushing code changes:

```sh
shopify theme check
```

## Branches

- `main` — connected to Shopify.
- `coco-dawn-backup` — the previous Dawn 16.0.0 "Coco Crochet" theme, kept for reference
  (can be reconnected in Shopify via Add theme → Connect from GitHub).

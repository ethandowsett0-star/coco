# Store setup files — Coco Crochet

Files used to set up the Shopify store. This folder is not part of the theme
(listed in `.shopifyignore`; the Shopify GitHub integration only syncs theme folders).

| File | Use |
|---|---|
| `coco-crochet-products-import.csv` | Shopify admin → Products → Import. Creates the 10 crochet pattern products (descriptions, prices, 66 photos) and their 6 collections. Photos are downloaded from the previous store's CDN during import, so run the import while `yourpattern.myshopify.com` is still online. |
| `coco-crochet-store-policies.docx` | Settings → Policies. One policy per page; paste each one into the matching field. Replace the `[bracketed]` details. |

## Prices (set in the CSV, 9 Sep 2026)

| Product | Collection | Previous | New |
|---|---|---:|---:|
| Avocado Keychain Crochet Pattern PDF | Bags & Accessories | 8.99 | 4.99 |
| Gypsophila Flower Pot Crochet Pattern PDF | Flowers & Plants | 3.99 | 4.99 |
| Adorable Kittens Crochet Pattern PDF | Animals & Amigurumi | 6.99 | 6.99 |
| Adorable Pony Crochet Pattern PDF | Animals & Amigurumi | 4.99 | 6.99 |
| Charming Gnome Crochet Pattern PDF | Dolls & Characters | 4.49 | 6.99 |
| Magic Snowman Crochet Pattern PDF | Seasonal & Holiday | 6.49 | 6.99 |
| Sunflowers Crochet Pattern PDF | Flowers & Plants | 7.49 | 6.99 |
| Creative Coasters Crochet Pattern PDF | Home Decor | 9.49 | 7.99 |
| Colourful Floral Bag Crochet Pattern PDF | Bags & Accessories | 5.99 | 8.99 |
| Sunflower Bag Crochet Pattern PDF | Bags & Accessories | 8.49 | 8.99 |

Ladder: quick makes 4.99 · amigurumi, flowers and seasonal 6.99 · home-decor set 7.99 · bags 8.99
(Etsy 2026 crochet-pattern range: 4–6 simple, 6–9 standard, 9–12 complex/bundles).

## Remaining manual steps in Shopify admin

1. Settings → Store details → Store name.
2. Products → Import the CSV.
3. Apps → install Shopify **Digital Products**, attach each pattern PDF, automatic fulfillment.
4. Settings → Policies → paste from the docx (Terms and Privacy: "Create from template", then add the digital products clause).
5. Navigation → Main menu: Home · Shop patterns (`/collections/all`, with the 6 collections as sub-items) · Contact (`/pages/contact`). Footer menu: Search + the policies.
6. Online Store → Themes → theme editor: logo, favicon, announcement bar text, then Publish.

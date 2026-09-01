# Coco Crochet — Shopify Theme

Custom Shopify theme for **Coco Crochet**, a handmade crochet store. Built on [Dawn](https://github.com/Shopify/dawn), Shopify's reference theme.

## Customizations

- **Brand palette**: warm cream / soft beige backgrounds, deep terracotta buttons, warm brown text, sage accent (see `config/settings_data.json` color schemes)
- **Typography**: Lora (serif) for headings, Assistant for body
- **Cozy styling**: rounded buttons, cards and inputs; hover lift animations; cart drawer with order notes enabled
- **Homepage** (`templates/index.json`): hero banner → welcome intro → bestsellers → brand story → benefits (handmade to order, premium yarns, gift-ready packaging) → FAQ → newsletter signup
- **FAQ page template** (`templates/page.faq.json`): create a page in Shopify admin and assign the `faq` template
- **Announcement bar**: handmade-to-order message (see `sections/header-group.json`)

## Workflow

This repo is connected to the Shopify store via the [Shopify GitHub integration](https://shopify.dev/docs/themes/tools/github). Pushes to `main` sync automatically to the theme.

## License

Dawn is licensed under the [MIT license](LICENSE.md).

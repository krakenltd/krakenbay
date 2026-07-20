# Kraken Bay Shopify theme

Custom Shopify Online Store 2.0 theme for Kraken Bay, based on Dawn.

## Local development

Install the Shopify CLI, authenticate with the Kraken Bay store, then run:

```sh
shopify theme dev
```

The editable theme files live at the repository root so the repository can be connected directly to Shopify through its GitHub integration.

## Main customisation

- `sections/kb-homepage-story.liquid` — homepage brand, buyer guidance, process and sustainability content
- `assets/kb-premium.css` — Kraken Bay visual system and responsive homepage styles
- `templates/index.json` — homepage section order and content settings

The original exported ZIP is retained in `Curent Theme/` as a local backup and ignored by Git.

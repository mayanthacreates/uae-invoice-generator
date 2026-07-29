# UAE tax invoice generator

Fills a VAT-ready invoice with TRN fields, line items and totals, previews it live, and exports to PDF.

Live: https://mayantha.ae/tools/uae-tax-invoice-generator

## How it works

One self-contained page - `public/uae-invoice-generator.html` holds the markup, styles and logic.
There is no backend and no build step. Nothing is uploaded anywhere; the work happens
in the browser.

## Running it

```sh
npx wrangler dev     # local
npx wrangler deploy  # to your own Cloudflare account
```

`wrangler.jsonc` serves `public/` as static assets. Deploying gives you a
`workers.dev` URL; add a `routes` entry if you want it on your own domain.

## Note

The live version linked above is a React port that runs inside mayantha.ae. This repo
is the original standalone implementation - same behaviour, no framework.

MIT licensed.

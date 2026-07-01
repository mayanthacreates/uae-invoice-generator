# UAE Invoice Generator

Free tool at https://mayantha.ae/uae-invoice-generator - a single static page served by a
Cloudflare Worker routed onto the mayantha.ae zone.

- `public/uae-invoice-generator.html` - the whole tool (self-contained HTML/CSS/JS)
- `wrangler.jsonc` - static assets Worker + zone route

Deploy: `npx wrangler deploy`

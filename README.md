# larynth-docs

Larynth documentation, built with Mintlify and published at docs.larynth.com.

## Layout

- `docs.json`: site config and navigation
- `index.mdx`, `quickstart.mdx`, `help/`: owner pages (set up and help)
- `concepts/`, `guides/`: developer pages
- `changelog.mdx`: release notes
- `api-reference/overlays/`: OpenAPI overlay that turns the playground off for endpoints that spend money or call a phone; it survives spec syncs
- `api-reference/`: API pages and `openapi.json` (copy of the public spec)
- `webhooks/`, `sdks/`: webhook and SDK pages
- `logo/`, `favicon.svg`, `style.css`: brand assets

## Work locally

```bash
npm i -g mint
mint dev
mint validate
mint broken-links
```

## Rules

Document only what exists in the API spec or code. Plain, calm, second person. No marketing words. Sample phone numbers are fictional 555 numbers.

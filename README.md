# larynth-docs

Larynth documentation, built with Mintlify and published at docs.larynth.com.

## Layout

- `docs.json`: site config and navigation
- `index.mdx`, `quickstart.mdx`, `concepts/`, `guides/`, `support.mdx`: guides
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

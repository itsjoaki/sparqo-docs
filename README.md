# Sparqo docs

Mintlify documentation for Sparqo. Live at docs.sparqo.ai.

## Preview locally

```bash
npm i -g mint      # Mintlify CLI (once)
mint dev           # serve at http://localhost:3000
```

## Connect to Mintlify

1. Push this folder to a new GitHub repo (for example `itsjoaki/sparqo-docs`).
2. In your Mintlify dashboard, connect that repo (install the Mintlify GitHub app).
3. Set the custom domain to `docs.sparqo.ai` and add the CNAME Mintlify gives you in Cloudflare DNS.

Every push to the default branch redeploys the docs.

## Structure

- `docs.json`: config, theme, navigation.
- `introduction.mdx`, `quickstart.mdx`: get started.
- `guides/`: one page per agent (Content & SEO, AI Visibility, Distribution) plus Connections and Brand.
- `favicon.svg`: the Sparqo mark.

# MD Integrations API Docs

API documentation for MD Integrations, built with [Mintlify](https://mintlify.com).

Scraped from the public Postman docs and converted to a proper OpenAPI 3.0 spec.

## Stats

- **1,054 endpoints** across **765 paths**
- **43 tags** auto-organized from Postman collection folder structure
- **1,013 endpoints** with descriptions
- **387** with request body examples
- **141** with response examples
- Bearer token (OAuth 2.0 Client Credentials) auth

## Setup

```bash
# 1. Create a GitHub repo and push
git init && git add . && git commit -m "Initial Mintlify docs"
git remote add origin git@github.com:YOUR_ORG/mdi-docs.git
git push -u origin main

# 2. Connect to Mintlify dashboard → Import from GitHub

# 3. Preview locally
npx mintlify@latest dev
```

> If your CLI expects `mint.json`, rename `docs.json` → `mint.json`.

## Customization

- **Logos**: Replace SVGs in `logo/` and `favicon.svg` with MDI branding
- **Colors**: Edit `colors` in `docs.json`
- **Guide pages**: Edit `.mdx` files to add more detail
- **OpenAPI spec**: Update `openapi.json` — sidebar updates automatically from tags

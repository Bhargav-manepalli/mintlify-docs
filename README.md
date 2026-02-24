# QIM Product SDK Docs (Mintlify)

This repository is a **Mintlify documentation site** for the Yocto layer:
- `meta-qcom-qim-product-sdk`

## Prerequisites
- Node.js **20.17+**
- Git

## Local preview
```bash
npm i -g mint
mint dev
```

If you prefer not to install globally:
```bash
npx mint dev
```

## Editing
- Update `.mdx` files.
- Adjust nav, branding, and settings in `docs.json`.

## Deploy
Connect this repository to the Mintlify dashboard (GitHub integration). Pushes to the default branch trigger deployments.

## Notes
This docs repo is intentionally separated from the Yocto layer repo to keep the Yocto metadata clean.

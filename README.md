# Hanzi Stroke Practice — Legal & Support

Public documentation for **[Hanzi Stroke Practice](docs/index.md)** (汉字笔顺字帖), an iOS app for generating Chinese stroke-order practice sheets.

## Pages

| Page | File | Purpose |
|------|------|---------|
| **Support** | [docs/index.md](docs/index.md) | App overview, dictionary coverage, contact, links to privacy policy (App Store **Support URL**) |
| Privacy policy (EN) | [docs/legal/privacy-policy-en.md](docs/legal/privacy-policy-en.md) | App Store **Privacy Policy URL** |
| Privacy policy (ZH) | [docs/legal/privacy-policy-zh.md](docs/legal/privacy-policy-zh.md) | 简体中文隐私政策 |
| Publishing notes | [docs/legal/README.md](docs/legal/README.md) | GitHub Pages setup and placeholder checklist |

## GitHub Pages

1. **Settings → Pages → Build and deployment → Source:** branch `main`, folder **`/docs`**.
2. After deploy, the support page is the site root:
   - Support: `https://<GITHUB_USERNAME>.github.io/<REPO_NAME>/`
   - Privacy (EN): `https://<GITHUB_USERNAME>.github.io/<REPO_NAME>/legal/privacy-policy-en`
   - Privacy (ZH): `https://<GITHUB_USERNAME>.github.io/<REPO_NAME>/legal/privacy-policy-zh`

Use the English privacy policy URL in App Store Connect unless Apple requests otherwise.

## Before publishing

Replace placeholders in the legal files (`[EFFECTIVE_DATE]`, `[SUPPORT_EMAIL]`) — see [docs/legal/README.md](docs/legal/README.md). The support page contact email is already set in [docs/index.md](docs/index.md).

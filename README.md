# Verificahub Uzbekistan documentation content

Source content for `docs.verificahub.uz`. Uzbek is the default in `docs/`; Russian and English translations live under `i18n/<locale>/docusaurus-plugin-content-docs/current/`. The Uzbek text prevails if translations differ.

`verificahub-docs-site-uz` copies `docs/`, `i18n/` and `registry/links.json` at build time. Pushing `production` here triggers a site deploy to GitHub Pages.

## Legal documents (`docs/legal/`)

| Page | Purpose |
|---|---|
| `public-offer.md` | B2B service agreement (acceptance, balance, billing per SMS sent, liability, disputes) |
| `refund-policy.md` | Refund of unspent balance within 30 days of a top-up |
| `privacy-policy.md` | Verificahub as owner/operator of account, visitor and support data |
| `personal-data-consent.md` | Text behind the personal data checkbox at account verification |
| `data-processing.md` | End-user phone numbers processed on the integrator's instructions |

Keep all three languages in sync and add new pages to `registry/links.json`. Obtain legal and acquiring-bank review before accepting payments.

Technical API endpoints and integration examples are intentionally omitted until the UZ API and its documentation are confirmed.

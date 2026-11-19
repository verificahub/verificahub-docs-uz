# Uzbekistan docs content rules

Markdown content for `docs.verificahub.uz`, built by `verificahub/verificahub-docs-site-uz`.

## Layout
- `docs/`: Uzbek (default locale).
- `i18n/ru/…`, `i18n/en/…`: Russian and English translations of the same pages. Keep all three in sync.
- `registry/links.json`: required by the site's sync script; copied to `/links.json`.

## Branches
- Work only on local `develop`; check the current branch before editing.
- `production` is the release branch. Don't edit or commit on it directly.
- Promote reviewed `develop` commits to `production` by fast-forward only (`git push origin develop:production`).
- Push only when the user explicitly asks. Force-push only when the user explicitly asks for it.

## Deploy
- A push to `production` runs `.github/workflows/trigger-site-deploy.yml`, which dispatches `docs-production-updated` to `verificahub-docs-site-uz` (secret `SITE_DISPATCH_TOKEN`). The site then builds this commit and deploys to GitHub Pages.

## Commits
- No `Co-Authored-By: Claude` trailers and no "Generated with Claude Code" lines in commits or PRs.

## Checks
- Preview or build from the site repo: `cd ../verificahub-docs-site-uz && npm run build` (reads `../verificahub-docs-uz`). Don't build or preview when the user asks not to.
- Legal pages (`docs/legal/`): confirm payment-provider, refund and data-handling facts before changing them.

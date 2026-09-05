# mundaneb3at.github.io

GitHub Pages root for the `mundaneb3at` GitHub account. This repo itself has no site content of
its own — its only job is to hold the account's Pages configuration (and, previously, a custom
domain that broke things — see below).

## What actually gets served here

Nothing directly. GitHub Pages for other repos on this account is served under this domain, e.g.
`https://mundaneb3at.github.io/sim-maker-kit/` (confirmed live, HTTP 200) — that page belongs to
the `sim-maker-kit` repo, not this one. If you're looking for a project demo, check the individual
project's own repo and README.

## Custom domain history

No custom domain is configured. A `CNAME` file pointing to `stosnia.me` was removed 2026-08-17:
that domain had no server listening on it, and its presence was 301-redirecting *every* Pages URL
on this account — including the `sim-maker-kit` demo above — to a dead endpoint. Re-add a `CNAME`
only once whatever `stosnia.me` should point to is actually live (verify first with `curl -sI`
before pointing anything at it again).

## License

MIT — see [LICENSE](LICENSE).

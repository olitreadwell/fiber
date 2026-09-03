# gofiber/fiber context
> refreshed 2026-09-03 | upstream default: main @ 0c5108d0

## Identity & policies
- upstream: gofiber/fiber, default branch main, primary language Go, English-first (yes — all docs/commits in English)
- CLA/DCO: none (no CLA bot, no DCO requirement in CONTRIBUTING)
- AI-assisted PR policy: unstated (no AI mention in CONTRIBUTING; no ai_disclosure_required)
- signed commits required: no (no branch protection on main)
- PR template: `.github/pull_request_template.md` (fill verbatim)
- external tracker: github

## Conventions (verified from merged PRs)
- branch naming: `<type>/<kebab-description>` (fix/..., docs/..., test/..., feat/..., chore/...)
- commit style: emoji-prefixed Conventional Commits (🔥 feat, 🐛 bug, 🩹 fix, 🧹 chore, 📚 doc, 🚨 test, 🎨 style)
- test command: `go test ./...` (per CONTRIBUTING)
- CI: GitHub Actions (lint, test, cspell); external PRs merge regularly (dependabot + humans)

## Maintainer picture
- active maintainers: gaby, ReneWerner87 (merge most PRs, fast turnaround)
- external contributors merge regularly (BitWeaverDev, evgenyponomarev, Rohilalala, lazerg)

## Issue-area health
- active, well-maintained; docs in /docs/ directory

## Gap ledger (dedupe — READ FIRST, never re-pick)
- 2026-09-03: dead-link cleanup PR #1 (fix/dead-links-docs) — 9 dead links fixed in README.md, docs/whats_new.md, docs/middleware/keyauth.md (contrib v3 paths, docs.gofiber.io /middleware/*, recipes envoy-extauthz). Do not re-pick these strings.

## Mined gaps (discovered, not yet attempted)
- (none yet)

# gofiber/fiber context
> refreshed 2026-10-12 | upstream default: main @ 9438d7e90ad36755d88f94c94461a7e86549461a

## Identity & policies
- upstream: gofiber/fiber, default branch main, primary language Go, English-first (yes — all docs/commits in English)
- CLA/DCO: none (no CLA bot, no DCO requirement in CONTRIBUTING)
- AI-assisted PR policy: unstated (no AI mention in CONTRIBUTING; no ai_disclosure_required)
- signed commits required: no (no branch protection on main)
- PR template: `.github/pull_request_template.md` (fill verbatim)
- external tracker: github

## Conventions (verified from merged PRs)
- branch naming: `<type>/<kebab-description>` (fix/..., docs/..., test/..., feat/..., chore/...); bot/agent branches also use ccr-..., codex/..., claude/...
- commit style: emoji-prefixed Conventional Commits (🔥 feat, 🐛 bug, 🩹 fix, 🧹 chore, 📚 doc, 📒 docs, 🚨 test, 🎨 style)
- test command: `go test ./...` (per CONTRIBUTING); `make markdown` runs markdownlint-cli2
- CI checks that gate merge: lint, unit (Go 1.26.x and 1.27.x on ubuntu/windows/macos), cspell, markdownlint, govulncheck, repeated, benchmark
- fork default branch `main`: fast-forwarded to upstream 9438d7e on 2026-10-12 (was 32 commits behind)

## Maintainer picture
- active maintainers: gaby, ReneWerner87 (merge most PRs, fast turnaround)
- external contributors merge regularly (BitWeaverDev, evgenyponomarev, Rohilalala, lazerg)

## Issue-area health
- active, well-maintained; docs in /docs/ directory

## Gap ledger (dedupe — READ FIRST, never re-pick)
- 2026-09-03: dead-link cleanup PR #1 (fix/dead-links-docs) — 9 dead links fixed in README.md, docs/whats_new.md, docs/middleware/keyauth.md (contrib v3 paths, docs.gofiber.io /middleware/*, recipes envoy-extauthz). Do not re-pick these strings.
- 2026-10-12: trivial cleanup PR #29 (docs/fix-dead-links-and-typos, off main @ 9438d7e) — 6 one-line fixes: .github/CONTRIBUTING.md stargazers link, .github/dependabot.yml help.github.com link, .github/SECURITY.md "it's"→"its", .markdownlint.yml md060 link (v0.34.0 predates the rule), client/README.md stale import (missing /v3), middleware/logger/config.go docs link. Do not re-pick these strings.

## Mined gaps (discovered, not yet attempted)
- 2026-10-12: typo sweep exhausted — codespell 2.4.3 and typos-cli 1.51.1 over the whole tree return zero genuine findings (remaining hits are deliberate test fixtures: caf/mis/byt/Fo/ONTENT/YPE/nd, "catch-alls"). Link sweep of ~620 real URLs found only the links in the ledger above. Re-run the tools on NEW files only, not the whole tree.
- (no un-attempted gaps yet)

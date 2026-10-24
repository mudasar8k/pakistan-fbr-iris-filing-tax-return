# Changelog

All notable changes to this project are documented here. This project adheres to
[Semantic Versioning](https://semver.org/).

## [1.1.0] - 2026-10-24

### Added
- `version` and `license` fields to `SKILL.md` frontmatter.
- New workflow coverage in `SKILL.md`: account preparation, foreign-employer and freelancer/export income, advance-tax handling, explicit gifts/loans and pass-through sections, and a correction/revision section (section G).
- Reference guides:
  - `references/documents-required.md`
  - `references/salaried-taxpayers.md`
  - `references/freelancers-foreign-income.md`
  - `references/wealth-statement.md`
  - `references/bank-reconciliation.md`
  - `references/withholding-tax.md`
  - `references/payment-cpr.md`
  - `references/common-errors.md`
  - `references/worked-examples.md` (fictional examples)
- Project meta files: `CONTRIBUTING.md`, `CHANGELOG.md`, `SECURITY.md`, `.gitignore`.
- GitHub Actions validation workflow (`.github/workflows/validate.yml`) checking SKILL.md frontmatter, internal Markdown links, and a basic privacy scan.

### Changed
- Rewrote `README.md`: structure overview, reference-guide index, ChatGPT/AI Skills installation steps, privacy section, and status badges. Removed the outdated "create a new repository" instruction now that the repo exists.
- Expanded `agents/openai.yaml` metadata.
- Strengthened the "never manufacture a balancing figure" safeguard throughout.

### Notes
- No tax rates, slabs, thresholds or deadlines are hard-coded; year-specific rules are flagged for verification against official FBR sources.
- No real taxpayer data is included; all examples are fictional.

## [1.0.0] - 2026-10-24

### Added
- Initial skill: `SKILL.md`, `README.md`, `LICENSE`, `agents/openai.yaml`,
  `references/fbr-official-sources.md`, `references/checklist.md`.

# Contributing

Thanks for helping improve the Pakistan FBR IRIS Filing Assistant. This project is **unofficial** and is not tax or legal advice.

## Before you open an issue or PR

- **Never** include real taxpayer data: no names, CNIC/NTN, IBAN/account numbers, PSIDs, CPRs, reference IDs, screenshots, statements, receipts, contact details or addresses.
- Describe problems with **redacted** or fictional examples only.
- Keep the project lightweight — prefer small, focused changes.

## What good contributions look like

- Corrections to outdated IRIS steps or links (cite the [official FBR source](references/fbr-official-sources.md)).
- Clearer, beginner-friendly guidance.
- Additional **fictional** worked examples.
- Privacy or accuracy safeguards.

## What we will not accept

- Invented tax rates, thresholds or deadlines stated as fact (they are year-specific — guidance must point users to verify).
- Any advice that manufactures figures (cash, gifts, loans, expenses) to force a zero reconciliation.
- Real financial data in any form.

## Accuracy standard

Tax rules change. Contributions should **flag** year-sensitive rules for professional verification rather than hard-coding numbers. When in doubt, add a disclaimer and a link to the official source.

## Technical checks

- Keep `SKILL.md` YAML frontmatter valid (`name`, `description`, `version`).
- Keep internal Markdown links working.
- The GitHub Actions `validate` workflow runs frontmatter, link and privacy checks on every push and PR.

## Pull request process

1. Fork or branch.
2. Make your change with a clear description (redacted).
3. Ensure the validation workflow passes.
4. Open the PR against the default branch.

By contributing you agree your contributions are licensed under the [MIT License](LICENSE).

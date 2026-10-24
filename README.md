# Pakistan FBR IRIS Filing Assistant

[![Validate](https://github.com/mudasar8k/pakistan-fbr-iris-filing-tax-return/actions/workflows/validate.yml/badge.svg)](https://github.com/mudasar8k/pakistan-fbr-iris-filing-tax-return/actions/workflows/validate.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Version](https://img.shields.io/badge/skill-v1.1.0-blue.svg)

A community-oriented **ChatGPT / AI Skill** that safely guides individuals through Pakistan's **FBR IRIS** income-tax filing and wealth reconciliation — including tax-payment (PSID) and CPR verification.

> **Unofficial; not affiliated with FBR. Not legal or tax advice.** Tax rules, menu labels and forms change. Verify the applicable tax-year law and confirm uncertain cases with a Pakistani tax professional.

## What it does

- Walks users through IRIS screenshots **one step at a time**.
- Covers **salaried, foreign-employer and freelancer** income without double-counting.
- Reconciles prior- and current-year **assets, bank accounts, cash, gifts and liabilities**.
- Separates **own-account transfers, reimbursements and pass-through funds** from real earnings.
- Explains **PSID payments, CPR recognition**, and how to verify an actual return submission.
- Supports **permitted corrections/revisions** without manufacturing figures.

> **Critical safeguard:** Never manufacture a cash balance, expense, gift or loan just to produce a zero unreconciled figure.

## Repository structure

```
.
├── SKILL.md                 # Skill entrypoint (YAML frontmatter + workflow)
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CHANGELOG.md
├── SECURITY.md
├── .gitignore
├── agents/
│   └── openai.yaml          # Interface metadata
├── references/
│   ├── fbr-official-sources.md
│   ├── checklist.md
│   ├── documents-required.md
│   ├── salaried-taxpayers.md
│   ├── freelancers-foreign-income.md
│   ├── wealth-statement.md
│   ├── bank-reconciliation.md
│   ├── withholding-tax.md
│   ├── payment-cpr.md
│   ├── common-errors.md
│   └── worked-examples.md
└── .github/workflows/validate.yml
```

## Getting started with IRIS (overview)

1. Have an active IRIS account (NTN/CNIC-based registration). See [Getting started & documents required](references/documents-required.md).
2. Select the correct **tax year** and return type.
3. Gather evidence — salary certificate, bank statements, withholding/advance-tax certificates. See the [checklist](references/checklist.md).
4. Complete income → wealth statement → reconciliation.
5. Generate a **PSID**, pay, and **verify the CPR**. See [payment & CPR](references/payment-cpr.md).
6. Submit, then confirm **both** the return and wealth statement are in **Completed Tasks**.

## Reference guides

| Guide | Purpose |
|---|---|
| [Documents required](references/documents-required.md) | What to gather before filing |
| [Salaried taxpayers](references/salaried-taxpayers.md) | Employment income workflow |
| [Freelancers & foreign income](references/freelancers-foreign-income.md) | Remote/export/foreign-employer income |
| [Wealth statement](references/wealth-statement.md) | Assets, liabilities, reconciliation |
| [Bank reconciliation](references/bank-reconciliation.md) | Opening/closing balances, own transfers |
| [Withholding & advance tax](references/withholding-tax.md) | Adjustable vs final tax |
| [Payment & CPR](references/payment-cpr.md) | PSID, CPR verification |
| [Common filing errors](references/common-errors.md) | Mistakes to avoid |
| [Worked examples](references/worked-examples.md) | Fictional end-to-end illustrations |
| [Official FBR sources](references/fbr-official-sources.md) | Links to verify current rules |
| [Accuracy & privacy checklist](references/checklist.md) | Pre-filing / pre-publish checks |

## Installation (ChatGPT / AI Skills)

This skill follows the `SKILL.md` + frontmatter format.

1. Download this repository (or clone it):
   ```bash
   git clone https://github.com/mudasar8k/pakistan-fbr-iris-filing-tax-return.git
   ```
2. Add the skill directory to a compatible Skills environment. `SKILL.md` is the entrypoint; the model reads its YAML frontmatter (`name`, `description`) to decide when to use the skill.
3. Keep the `references/` folder alongside `SKILL.md` — the workflow links to those guides.

To package for distribution, zip the project root so that `SKILL.md` sits at the top level of the archive.

## Privacy

No taxpayer-specific statements, receipts, screenshots, CNIC/NTN, IBANs or payment receipts are included in this repository, and none should ever be committed. All examples are **fictional**. See [SECURITY.md](SECURITY.md) and the [checklist](references/checklist.md).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Open an issue or pull request with a **redacted** description of the problem — never post personal or financial data.

## License

[MIT](LICENSE).

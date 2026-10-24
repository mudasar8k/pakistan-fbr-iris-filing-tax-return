# Security & privacy policy

This project handles **guidance only** and must never contain real taxpayer data.

## Reporting a vulnerability or privacy issue

If you find a security problem, or any committed file that leaks personal/financial data, please:

- Open a GitHub issue **without** including the sensitive values, or
- Contact the maintainer privately if the issue itself would expose data.

Describe the problem with redacted or fictional examples. We aim to acknowledge reports promptly.

## Data that must never be committed or shared

- Passwords, OTPs, PINs, security answers, session URLs or login credentials.
- Full CNIC / NTN numbers.
- IBANs, bank account numbers, card numbers.
- PSIDs, CPRs, challan numbers, transaction/reference IDs.
- Real bank statements, tax PDFs, IRIS exports, email confirmations.
- Screenshots containing any of the above.
- Names, phone numbers, email addresses or precise home addresses.

## Guardrails built into the skill

- The assistant never asks for credentials, OTPs or full identifiers.
- All examples are fictional and clearly labelled.
- Users are told to share only **redacted** documents, and only the pages needed for a step.

## Repository hygiene

- `.gitignore` excludes common sensitive/local file types.
- The CI validation workflow runs a basic scan for obvious secret/PII patterns in tracked files.
- A passing scan is **not** a guarantee — reviewers must still manually check any contributed example.

> This policy supports privacy; it is not a substitute for your own legal and data-protection obligations.

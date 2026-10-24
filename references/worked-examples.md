# Worked examples (fictional)

> **All figures, names and situations below are entirely fictional** and for illustration only. They do **not** use any real taxpayer data, and they do **not** state current tax rates — tax computation depends on year-specific law you must verify. Not tax advice.

---

## Example 1 — Salaried individual, single employer

**Persona:** "Ayesha", resident, one employer for the full year, one savings account.

| Item | Amount (PKR) | Source |
|---|---|---|
| Gross salary | 2,400,000 | Salary certificate |
| Tax deducted by employer | 180,000 | Salary certificate (adjustable) |
| Bank profit | 30,000 | Profit certificate |
| Tax on bank profit | 4,500 | Profit certificate (adjustable) |

**How the assistant helps:**
- Enters salary under Employment; bank profit under Other Sources — not merged.
- Records both tax deductions as **adjustable** credits (not double-counted).
- Does **not** state the final tax due — that depends on the year's slabs, which must be verified in IRIS/official law.

**Wealth sketch (illustrative only):**
```
opening net wealth      5,000,000
+ income (salary + profit, net of tax & expenses)
− living expenses (user-reported, by category)
= closing net wealth    (must match assets − liabilities)
```
If the unreconciled amount is non-zero, the assistant looks for a missing transaction — it never plugs cash.

---

## Example 2 — Freelancer with foreign clients

**Persona:** "Bilal", resident freelancer, two foreign clients paid via bank remittance.

- Gross export receipts: PKR 3,600,000 (from bank remittance records).
- Platform/gateway fees: PKR 120,000 (with evidence).
- A friend sent PKR 200,000 and Bilal forwarded PKR 200,000 the same week for a shared laptop purchase — **pass-through**, excluded from income and expense.

**How the assistant helps:**
- Classifies the two client inflows as export receipts; flags any **export/final-tax concession** as needing verification (eligibility, PSEB status, banking-channel conditions).
- Excludes the PKR 200,000 pass-through on both legs.
- Records gateway fees only with support; does not estimate to balance wealth.
- Flags residency/foreign-tax-credit questions for a professional.

---

## Example 3 — Reconciliation gap handled correctly

**Persona:** "Sana", salaried, notices an **unreconciled amount of PKR 150,000**.

**Wrong approach (the skill refuses):** increase "cash in hand" by PKR 150,000 to make it zero.

**Correct approach:**
1. Re-check each bank account's opening/closing balances.
2. Confirm no own-account transfer was counted as income.
3. Look for a missing profit credit or an under-reported expense.
4. Finding a forgotten PKR 150,000 fixed-deposit maturity transfer between her own accounts, she removes the double-count — the gap closes **with a real reason**.

The lesson: a zero unreconciled figure must come from a corrected fact, never a manufactured one.

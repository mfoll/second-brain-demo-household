---
type: Source
source_type: Internal document
date_accessed: 2026-10-22
belongs_to: "[[run-family-health-admin]]"
related_to:
  - "[[sensitive-records-stay-at-source]]"
  - "[[moms-care-documents-index]]"
  - "[[household-records-and-privacy]]"
_organized: true
---

# Family Health Records Index

Where each person's health records live and who can open them. This note is a map, not a record: it holds no diagnoses, results, medications or visit notes, and it never will. Mom's equivalent is [[moms-care-documents-index]].

## Summary

One row per family member: primary providers, the patient portal that holds their records, and who holds access. Plan and insurance details point to Bitwarden (card images, member IDs) and Paperless-ngx (explanation-of-benefits statements). Last checked 2026-10-22, after the 2027 plan decision.

## Key Details

| Person | Primary care | Dentist | Records live in | Portal access |
|---|---|---|---|---|
| Nathan | [[lionel-grant]] | [[hana-kovar]] | Practice patient portal; dental office portal | Nathan; Renata has emergency access to Nathan's Bitwarden, which holds the login |
| Renata | Lionel Grant | Hana Kovar | Same portals, her own accounts | Renata; Nathan through Bitwarden emergency access |
| Maya (17) | Lionel Grant | Hana Kovar | Practice portal, minor account | Both parents as proxies until 18; from 18 only with her consent |
| Eli (15) | Lionel Grant | Hana Kovar | Practice portal, minor account; physical therapy clinic portal for 2026 | Both parents as proxies |
| Margaret | [[amira-saleh]] | Her own dentist | Her clinic's patient portal | Margaret; Nathan as proxy since 2025-04-22. See [[moms-care-documents-index]] |

Plans and cards:

- Health plan: Brackwater high-deductible plan for 2026, copay plan from 2027-01-01 ([[open-enrollment-2027]]). Administered by Tessaline Health; member portal login in Bitwarden, "Health" collection.
- Dental and vision: Brackwater dental and vision plans, unchanged for 2027 ([[brackwater-dental-and-vision-plans-2027]]).
- Insurance card images: Bitwarden, as attachments on the plan's item. Not in Paperless, not on phones' photo rolls.
- Explanation-of-benefits statements: downloaded quarterly to Paperless-ngx, tagged `health` and the person's name. The vault refers to totals only.
- HSA: Tessaline Health portal; statements in Paperless-ngx ([[hsa-account-summary-2026-10]]).

What the vault may record about health: appointment dates and providers when they matter for logistics, plan choices, premiums, deductibles, claim totals, and admin-level reasons ("Eli's sports injury"). Nothing else. The reasoning is in [[sensitive-records-stay-at-source]].

## Caveats

- Maya turns 18 in 2027. Proxy access ends unless she grants it, and that is her choice. Calendar reminder set for her birthday month.
- The physical therapy clinic used in 2026 has its own portal; Eli's account there closes after a year of inactivity. Nothing in it needs keeping on our side.
- If a provider changes, update this table and the Bitwarden item in the same sitting.

## Source Location

This note is the index itself. Logins and card images: Bitwarden family organization, "Health" collection. Statements: Paperless-ngx, tag `health`. See [[household-document-archive]].

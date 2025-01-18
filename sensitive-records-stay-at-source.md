---
type: Opinion
status: Active
confidence: High
belongs_to: "[[support-moms-care]]"
related_to:
  - "[[household-records-and-privacy]]"
  - "[[moms-care-documents-index]]"
  - "[[family-health-records-index]]"
_organized: true
---

# Sensitive Records Stay At Source

## Stance

> [!info]
> The vault points to medical and financial records and never copies them. It records where something is, who can open it and what we decided; the record itself stays in the patient portal, Bitwarden, Paperless-ngx or the fire safe.

## Scope

- Medical: diagnoses, test results, medications, symptoms, care notes. For all of us, and especially for Mom, whose records are in the Wrenfield Family Clinic portal.
- Financial and identity: account, policy, card, loan and tax ID numbers, logins, full statements.
- Does not cover totals and decisions. "The deductible is $4,000", "Mom pays 60% of the aide" and "Nathan has proxy access" belong in the vault, because they are what we decide with.
- Applies to the children in a stronger form: schedules, deadlines and logistics only.

## Why I Think This

- **The vault is copied around.** It is plain Markdown in Git, synced to two laptops, read by Renata and by an AI assistant. Every copy of a medical detail is one more place it can leak or go stale.
- **Stale copies are worse than none.** A medication list in a note from March is wrong by July. The portal is right by definition.
- **Mom asked.** In 2025-04, when Nathan got proxy access, Mom asked who else would see her information. "Only me, in the portal" was an answer she accepted. The [[moms-care-documents-index]] is how we keep that promise.
- **Pointers are what we actually need.** At 2:00 when the pendant service calls, nobody needs a diagnosis from the vault; they need to know where the healthcare proxy is and who to call ([[respond-to-a-pendant-alert]]).
- It is the same habit Nathan uses at work with client data: reference the controlled copy, never paste it into the meeting notes.

## Trade-offs

- Some questions need two systems: "what did the specialist bill?" means the portal plus the [[family-health-records-index]]. Slower, accepted.
- If the home server dies, Paperless pointers are dead until restore. Mitigated by the backup in [[household-document-archive]].
- The AI assistant cannot answer anything clinical from the vault. That is the point.
- When Eli's sports injury ran through the deductible in 2026, it was tempting to log visits here. We logged the costs and counts only.

## What Would Change My Mind

- A care emergency where a pointer was not enough and the delay mattered. Then I would consider a sealed emergency summary in Bitwarden, still not in the vault.
- Mom asking for something else.

## Implications

- New notes about care say "Mom's January 2025 fall" or "an appointment with Dr. Saleh" and stop there.
- Sources about documents cite a Paperless ID and a short description, never the content.
- When processing the Inbox, strip any number or clinical detail before filing, and say so in the commit.

---
type: Procedure
status: Active
belongs_to: "[[manage-family-finances]]"
related_to:
  - "[[household-document-archive]]"
  - "[[paperless-tagging-scheme]]"
_organized: true
---

# File A Paper Document

From paper (or an emailed PDF) to Paperless-ngx, and into the vault when it matters.

## Steps

1. Scan on the office scanner to the Paperless consume folder, or forward the PDF to the Paperless mail inbox. One document per file.
2. In Paperless-ngx: set the correspondent, document type and date; title as `YYYY-MM-DD correspondent short description` ([[paperless-tagging-scheme]]).
3. Tag by area, add `tax-YYYY` if the return will need it, add a person tag if it concerns one person.
4. If it contains anything that lets someone act as us (a policy number, account number, ID card), also put that value or image in the right Bitwarden collection. Do not type it anywhere else.
5. Decide where the paper goes:
   - Original that must stay physical (will, deed, title, birth certificate, power of attorney): fire safe.
   - Anything else: shred.
6. If the document changes a decision, a balance or a coverage, update the relevant vault note and cite it as `paperless_id` with a one-line description. Do not paste its content.

## Guardrails

- Medical documents: file them, but nothing clinical goes into a vault note ([[sensitive-records-stay-at-source]]).
- Documents about Mom go under tag `mom` and stay readable by Claire's limited account; her records themselves stay in her clinic portal ([[moms-care-documents-index]]).

## Verification

The document is findable by tag and correspondent, and any vault note that refers to it shows its ID.

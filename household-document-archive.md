---
type: Source
source_type: Internal document
date_accessed: 2026-09-06
belongs_to: "[[manage-family-finances]]"
related_to:
  - "[[household-records-and-privacy]]"
  - "[[sensitive-records-stay-at-source]]"
  - "[[bitwarden-organizations-overview]]"
_organized: true
---

# Household Document Archive

How the family's documents are split between three places, and how vault notes refer to them. Written in 2025-02 during the [[household-budget-reset]], revised 2026-09-06 after the home server disk swap.

## Summary

- **Paperless-ngx** on the home server holds scans and downloaded PDFs: statements, invoices, policies, school notices, tax returns, receipts.
- **Bitwarden** (family organization) holds anything that would let someone act as us: logins, policy and account numbers, card images, tax and government identifiers, Wi-Fi and alarm codes.
- **The fire safe** in the basement holds originals that must stay physical: wills, Mom's power of attorney and healthcare proxy, the house deed, birth certificates, passports and car titles.
- **The vault** records what a document is, what it decided, where it is, and who can open it. It does not copy content that belongs in one of the three.

## Key Details

How notes cite each system:

- Paperless-ngx: `paperless_id: 1307` in frontmatter plus a one-line description in `## Source Location`. Document IDs are stable; titles in Paperless may be renamed.
- Bitwarden: by collection name only ("Insurance", "Health", "Money", "House", "Kids", "Mom"). Never by item name if the item name contains a number.
- Fire safe: "original in the fire safe", nothing more. The combination is in Bitwarden and known to Renata and me.

Paperless-ngx conventions:

- Tags: `tax-YYYY`, `insurance`, `health`, `legal`, `house`, `car`, `school`, `mom`, `budget`, `warranty`, plus a person tag (`maya`, `eli`) where it helps. Correspondents set for each insurer, bank and provider.
- Inbox processed at the [[monthly-money-meeting]]; anything left untagged for a month gets looked at.
- Scanning and filing steps: [[file-a-paper-document]]. Tagging scheme in full: [[paperless-tagging-scheme]].

Bitwarden setup: Renata and I are both owners; Maya has a member account with access to the "Kids" collection only; Claire has access to the "Mom" collection. Emergency access is set between Renata and me. Details in [[bitwarden-family-organization-setup]].

Backups: Paperless-ngx exports nightly to an external disk and weekly to an encrypted offsite copy. The vault itself is in Git.

## Caveats

- If the home server is down, nothing in Paperless can be read. The 2026-09 disk swap took it offline for two days; the export was fine but we had no way to read a policy during that window. Since then the current insurance declarations are also saved as Bitwarden attachments.
- The vault describes systems; it does not prove what is in them. When a fact matters (a balance, a coverage limit), check the source document.
- What happens to all of this if something happens to us: [[if-something-happens-to-us]].

## Source Location

This note is the reference. Paperless-ngx on the home server; Bitwarden family organization; fire safe in the basement utility room.

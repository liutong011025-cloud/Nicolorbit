---
name: nicolorbit-check-citations
description: Reconcile a manuscript's in-text citations with a supplied reference list, repair verifiable omissions, and highlight unresolved or unmatched items by category. Use when checking APA citation correspondence across an article and bibliography file.
---

# Nicolorbit Check Citations

Compare the supplied article and reference-list file bidirectionally. Preserve the article and bibliography wording except for verified citation repairs, added references, and requested highlighting.

## Normalize before matching

- Extract narrative and parenthetical citations, including grouped citations, suffix years, organizations, `et al.`, and same-surname authors.
- Parse each reference entry into authors, year, title, source, and DOI or URL where present.
- Match on normalized author identity and year, then use title and DOI metadata to resolve ambiguous cases. Do not treat spelling variants or year discrepancies as exact matches without verification.

## Reconcile both directions

- For every in-text citation, find the corresponding reference-list entry.
- For every reference-list entry, find at least one genuine in-text citation. Do not count incidental author-name mentions as citations.
- Identify duplicate references, conflicting metadata, citation-year suffix problems, and grouped citations containing only partially matched works.

## Repair verifiable omissions

- When an in-text citation has no reference entry, search authoritative publisher and DOI records immediately. If the exact work is verified, add its complete APA 7 entry to the reference list and keep the in-text citation unhighlighted.
- Correct clear bibliographic metadata errors only when the exact work is confirmed. Preserve a trace of substantive corrections in the final report.
- Never fabricate or guess a missing reference. If several works could match or the exact work cannot be verified, leave the citation in place and highlight it.
- Do not invent an in-text use for a bibliography item that the article never cites.

## Apply highlights

Use editable document highlighting and explain the legend in the document or delivery note:

- Yellow: an in-text citation has no confidently verified reference entry after searching.
- Turquoise: a reference-list entry is not cited in the article.
- Pink: a probable match has conflicting author, year, title, or DOI metadata and needs human review.

Apply color only to the smallest meaningful citation or full reference entry. Do not highlight surrounding prose. If the two supplied files are separate, return an annotated copy of each file that contains issues; also provide a consolidated corrected version when the user's workflow makes that useful.

## Verify and report

- Re-run the bidirectional match after repairs. Count matched citations, added reference entries, uncited bibliography entries, unresolved in-text citations, metadata conflicts, and duplicates.
- Render edited DOCX files and inspect highlights, hanging indents, pagination, tables, headers, and footers.
- Deliver the annotated files and a short reconciliation report with the color legend and exact unresolved items.


---
name: nicolorbit-translate-ppt
description: Translate and localize existing PowerPoint decks into polished English while preserving the original visual style, emphasis hierarchy, media, and layout. Use for PPT/PPTX translation when source links should be checked for official English wording, selected slides need template recoloring, or English text must be fitted without disrupting the deck.
---

# Nicolorbit Translate PPT

Translate the requested slide range and preserve the user's current file as the source of truth. If the presentation is open and has unsaved edits, save a working copy first so recent user changes are included.

## Confirm the scope from the latest instruction

- Treat the user's newest page range and requested operations as authoritative.
- Distinguish translation from visual-only edits. Never replace text on slides assigned only for recoloring or template alignment.
- Leave slides outside the requested scope byte-for-byte unchanged when practical.
- Save to a new output file unless the user explicitly requests overwriting.

## Inspect before editing

1. Inventory slide count, dimensions, editable text, images, charts, tables, hyperlinks, videos, animations, notes, and embedded files.
2. Render the source slides and identify the deck's visual system: background colors, title treatment, accent colors, type scale, margins, footer style, and recurring layouts.
3. Identify inconsistent slides and choose nearby representative slides as visual references.
4. Record the requested page ranges separately for translation, recoloring, and untouched content.

## Translate with source fidelity

- Translate meaning and teaching intent, not Chinese syntax. Use natural professional English suitable for presentation delivery.
- Follow the terminology already used in the deck. Keep names, dates, citations, numbers, and technical terms accurate.
- For quoted material, report titles, policy wording, research summaries, and footer links, open the cited source when accessible and use its official English title or wording. If no official English version is available, translate faithfully and do not imply that the translation is official.
- Preserve the original emphasis hierarchy. Keep headings and originally emphasized phrases bold; keep ordinary body paragraphs regular.
- Preserve paragraph structure, numbering, bullets, and relationships between labels and explanations.
- Do not translate text baked into screenshots, videos, or external interfaces unless the user explicitly asks for image or video editing.

## Preserve typography and layout

- Use Times New Roman for editable English text unless the user specifies another font.
- Start from the original font size. Reduce it only when English expansion causes overflow, using the smallest reduction that restores comfortable fit.
- Prefer widening a text box, adjusting line breaks, tightening paragraph spacing slightly, or making small positional corrections before materially shrinking type.
- Maintain safe margins and avoid collisions with images, charts, footers, and page edges.
- Do not use automatic text fitting if it produces inconsistent sizes across similar slides.
- Keep charts, tables, diagrams, hyperlinks, animations, and embedded media native and editable where they already are.

## Align inconsistent slides to the deck

- Reuse the dominant dark navy background, title color, accent colors, and spacing from representative slides in the same section.
- Adapt text and object colors for contrast while preserving existing highlighted words and semantic color coding.
- Do not flatten slides into images or replace a whole slide with a screenshot.
- Preserve the user's existing translated wording on slides requested only for template changes.

## Verify before delivery

1. Render every modified slide at presentation size.
2. Inspect for clipped text, overflow, awkward wraps, overlaps, low contrast, stray bullets, inconsistent bolding, and footer collisions.
3. Verify that all editable translated text uses the requested font and that body paragraphs are not entirely bold unless the source was.
4. Verify hyperlinks, videos, animations, charts, tables, and embedded files remain present.
5. Compare untouched slides and visual-only slides against the saved source copy to confirm their text was not changed.
6. Re-run package and layout validation after the final correction.
7. Deliver one clearly named PPTX and briefly state the edited ranges and any image/video text intentionally retained.

If source research is blocked, complete the remaining translation and layout work, label translated quotations accurately, and report only the specific limitation that affects the deliverable.


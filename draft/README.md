# Draft-page convention

Pages in this directory are reviewable drafts for workgroup calls.

- Name a call deck `meeting-N.html` here, without `draft` in the filename.
- Review it at `/draft/meeting-N.html`.
- When approved, promote it without changing the basename:
  `git mv draft/meeting-N.html meeting-N.html`.
- Preserve slide fragment identifiers such as `#2` so links continue to point
  to the same slide before and after promotion.
- Do not link draft pages from the public site index.

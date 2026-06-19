To use the real Acier BAT font for the headers:

1. Get the web font files (Acier BAT Text Solid) — buy/download from
   Commercial Type (commercialtype.com). You'll want the .woff2 (and
   optionally .woff) web format.

2. Rename and drop them in THIS folder so the paths are exactly:
       fonts/AcierBAT-TextSolid.woff2
       fonts/AcierBAT-TextSolid.woff

3. Commit & push. The site is already wired to load them via @font-face
   in index.html — no code change needed. Until the files exist, the
   headers fall back to "Anton" (a free look-alike).

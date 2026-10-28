# Strength & Shield Roofing — concept website

A single-page concept site for **Strength & Shield Roofing, LLC**, an owner-operated
roofer in McKinney, TX (Ryan Fritz; 5.0★, 54 Google reviews; BBB Accredited). Built as a
pitch preview by Rashad — not the official Strength & Shield Roofing website.

## The idea
The hero is an **honest hail inspection**. A real shingle photo with a chalk 10×10 test
square; visitors drag an inspector's loupe across it to find hidden hail hits, which get
circled in chalk. Light hail ends in "Repair, not replace" (from a real review about Ryan
recommending a repair instead of a new roof); a bad hailstorm ends in "Worth an insurance
claim". It's an illustration, labeled as such on the page.

## Build
- Single `index.html`, inline CSS + vanilla JS (canvas), no build step or dependencies.
- Photos in `images/` are free Unsplash stock placeholders: `shingles.jpg`, `roofer.jpg`,
  `inspection.jpg`, `crew.jpg`.
- Fonts: Rubik + Inter + Shadows Into Light (Google Fonts).
- `window.ssInspection.hits()` is a read-only hook used for automated testing.
- Marked `noindex, nofollow`; footer labels it a concept preview.
- Inspection form is front-end only — connect Formspree / Web3Forms before launch.
- `[CONFIRM WITH CLIENT]` tags: licensing, insurance, warranties, adjuster meetings,
  exterior services, cities served.

# Three Sisters Hotel — landing page (concept rebuild)

A conversion-optimized, boutique redesign of the Three Sisters Hotel landing page
(reference: https://www.threesistershotel.ee/).

## How to open
`index.html` is a **single self-contained file** — just double-click it
(or drag into a browser). It pulls fonts from Google Fonts and photos from the live
threesistershotel.ee server, so it works online with no local server needed.

To preview with a local server instead:
```
cd ~/three-sisters-landing
python3 -m http.server 8080
# then open http://localhost:8080/index.html
```

## Current state (saved 2026-10-02)
- **Fonts:** Cormorant Garamond (titles) + Jost (body). Max 2 families.
- **Layout:** fully boxed — zero rounded corners anywhere; hairline-framed image plates
  with italic captions beneath; split editorial hero showing the three gables.
- **Hero copy:** "Boutique luxury behind medieval walls." + emotional sub
  ("Sleep inside 14th-century merchant houses … only 23 intimate rooms, each with its own
  quiet story to tell.")
- **Icons:** Phosphor (light weight, MIT) in the facts row.
- **Buttons:** soft-rectangle luxury style → now squared (uppercase, letter-spaced, arrows).
- **CRO:** booking widget pulled into the hero area with a question prompt; "Book direct"
  perks; star-rating review cards; "As featured in" strip under the hero + in reviews.
- **Skim bolding** on key phrases throughout.

## Open items (not done)
1. **Title font** — still Cormorant (flagged as a common/template serif). Candidates
   previewed: Fraunces, Bodoni Moda, Marcellus, Libre Caslon Display.
2. **Press logos** — currently styled text wordmarks. Drop official logo files into
   `logos/` (see `logos/README.txt`) to show the real logos; a JS fallback keeps
   wordmarks until then. Only use logos for outlets that genuinely featured the hotel.
3. **Booking widget** — not wired to the real Cloudbeds booking URL yet.

## Files
- `index.html` — the page.
- `logos/` — drop-in slot for official press logos (+ instructions).
- `references/` — font/button/title comparison sheets used during the design.

# Garage Floor Coatings page: educational deep dive

Date: 2026-10-17. Approved by Lukas in session.

## Goal
Replace the generic 200-word garage page with a long, educational page that explains
how Designer Floorzzz installs a flake garage floor and why the two-day epoxy-base
method outlasts one-day polyurea installs. Target searches: "epoxy garage floor Tampa",
"polyurea vs epoxy garage floor", "one day garage floor coating problems".

## Scope
- Rewrite `garage-floor-coatings.html` only. `decorative-flake.html` gets a short
  link-in later (separate task). No shared CSS changes except additive classes for
  the new sections and inline SVG diagrams.
- Keep existing header, top bar, footer, nav, hero markup pattern.

## Verified facts (from Lukas, 2026-10-17)
- Prep: 30-grit diamond grind, moisture test, XPS crack/joint filler.
- MVB (moisture vapor barrier) applied when the moisture test calls for it.
- System: XPS epoxy base coat, full flake broadcast, XPS polyaspartic topcoat.
- Two days on site. Day 1 prep + base + broadcast. Day 2 scrape + topcoat.
- Foot traffic 18 hours after topcoat. Vehicles 48 to 72 hours.
- Metallic floors use polyurethane or T200 topcoat; that goes on the metallic page, not here.

## Content rules
- Mechanism-based claims only (why something happens). No invented percentages.
- Humble tone, no bravado. Em dashes allowed in web copy.
- Do not claim lifetime warranty. "Warranty on select floor systems" wording only.

## Page sections
1. Hero: "Garage Floor Coatings in Tampa Bay" / "Done right in two days".
2. Two-day process with timeline graphic.
3. System layer by layer with cross-section diagram (concrete profile, MVB, epoxy base, flake, polyaspartic).
4. Epoxy base vs polyurea base with side-by-side diagram.
5. Why many one-day floors fail.
6. Full broadcast vs partial with illustration.
7. Hot tire pickup section.
8. FAQ (walk/park times, lifespan, one-day, moisture test, MVB cost, hot tire).
9. Photo strip + quote CTA.

## Visuals
Four inline SVGs in site palette (#7c3aed purple, #0a0a0a dark, grays). Responsive via viewBox.
Real photos from gallery/flake-*.jpg.

## Done when
Page renders correctly at 1366px and 390px, all links valid, no new console errors,
word count over 1,000, Lukas reviews copy for accuracy before it goes to cPanel.

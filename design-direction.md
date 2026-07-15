# Poppa Wahoo: design direction

## Step 2 diagnosis (poppawahoo.com on Guidesly)
1. No visible pricing anywhere on-page: prices hidden in JSON-LD and behind the Guidesly calendar while FishingBooker (which takes 15-20% commission) shows them plainly.
2. Broken schema: malformed phone (+1+13053945350), priceRange "trips from $3", no street address/geo, personal gmail leaked in Organization block.
3. The story (father tribute, Bush/Ted Williams provenance, celebrity-client captains, Discovery credit, veteran-owned) is buried on subpages; homepage is generic Guidesly Roboto-blue template.
4. Live template bug: /territory/poppa-waho renders "undefined Trips."
5. Worth preserving: the logo, the excellent boat/catch photography, the 7 named 5-star reviews, the real FAQ content, trip structure and prices.

## Step 3 competitive notes
Islamorada charter sites: teal/ocean-blue templates, Oswald/Roboto type, species sliders, FishingBooker widgets, "#1 rated" badges. None lead with editorial heritage; none show a rate board up front. Differentiation: sporting-magazine serif editorial + posted rates as an act of confidence ("posted like Poppa would want").

## Design Direction Declaration
Heritage editorial luxury sourced from the brand's own logo: royal blue and rod-and-reel gold on ivory, set in Fraunces like a well-printed fishing column. The signature element is the pairing of the dock rate board overlapping the hero (their prices, finally in daylight) with the Bob-Epstein-and-President-Bush legacy spread; neither could sit on any other charter site. Deliberately avoided: teal ocean gradients, species-card carousels, booking-widget dependence, and the SaaS stats bar.

## Section architecture and structural variation
1. Hero: full-bleed flagship photo, serif H1 (photo-led).
2. Rate board: navy strip overlapping the hero bottom by -72px (the overlap element).
3. Legacy: opens with an oversized italic pull-line, then photo-figure + editorial column + inline fact strip (no centered header).
4. Flagship: full-bleed image band with chip specs (breaks container).
5. Fleet: 3-card grid, the only card grid on the page; CTAs bottom-aligned by flex.
6. Trips & Rates: grouped ledger rows (photo chip / copy / price+CTA), a completely different structure from the fleet cards.
7. Captains (dark): 2 photo lead cards + 2 text-led legend panels + crew avatar note (three different card anatomies by design).
8. Reviews: featured serif pull-quote + 3-column divided strip (no cards).
9. Seasons: compact dark 2-col strip.
10. FAQ split + accordion; 11. Contact dark 2-col; 12. Footer.
Small-caps kickers on exactly 3 content sections (flagship, captains, contact).

## Blacklist temptations and avoidance
- SaaS stats bar: replaced with the rate board (numbers with prices are conversion, not decoration) and an inline fact strip inside the legacy column.
- Identical card grid: fleet cards vs trip ledger vs captain cards all structurally distinct.
- Fabricated credibility: rating shown only as "5.0 across every published charter review" (7 reviews, all named, all real); no invented Google counts.
- Em dashes: zero (verified by grep).
- White-out logo: dark surfaces use a background-removed (not inverted, not recolored) copy of the real logo.

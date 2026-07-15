# The Poppa Wahoo Collective

- Business: The Poppa Wahoo Collective, 84001 Overseas Hwy, Islamorada, FL 33036
- Target site rebuilt from: https://www.poppawahoo.com/ (Guidesly SaaS template)
- Build date: 2026-07-15
- Repo: crossfiber/poppa-wahoo
- Live: https://crossfiber.github.io/poppa-wahoo/

## Fonts (Google Fonts)
- Fraunces 500/600/700 + italics (headlines) + Figtree 400-700 (body)
- URL: https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,500;0,9..144,600;0,9..144,700;1,9..144,500;1,9..144,600&family=Figtree:wght@400;500;600;700&display=swap

## Palette (sourced from the brand logo)
- #3E63AC royal blue: sampled from logo lettering (#4664B4 family)
- #C29A3B gold: sampled from logo rod/reel linework (#BE963C family); CTAs only, navy text
- #0D1B33 / #14264A navy darks: deepened from the logo blue
- #F8F5EE / #EFE8D9 ivory neutrals

## Design direction (1 paragraph)
Heritage editorial luxury: the family that literally wrote the book on Keys fishing gets a site that reads like a well-set sporting magazine. Fraunces serif with italic accents, logo-derived navy and gold, and two signature moves: the dock rate board that overlaps the hero (fixing their worst conversion problem, hidden prices) and the legacy section led by the real photo of Bob Epstein with President George H. W. Bush.

## Data notes
- Prices from the business's own published schema + FishingBooker listing: half day $1,475, 3/4 $1,975, full $2,475, shark $1,000, swordfish $2,700, nearshore from $1,050, sunset $575, sandbar $800.
- Shark trip price conflict upstream: their site schema says $1,000, FishingBooker says $895. Used $1,000 (their own site). CONFIRM WITH CLIENT.
- Cancellation copy uses the FishingBooker policy (free to 30 days out) because their own site contradicts itself (24 hr vs 30 days). CONFIRM WITH CLIENT.
- aggregateRating 5.0/7 mirrors the 7 named reviews published on their current site.
- Geo coordinates approximate for 84001 Overseas Hwy; refine when GBP is claimed.
- Email set to info@poppawahoo.com (directory-verified). Their old site leaked personal gmail + iCloud addresses; those are gone. CONFIRM the info@ inbox is monitored.

## Remaining placeholders / client asks
- [REAL PHOTO NEEDED: Capt. Skip Bradeen] (his legend card is deliberately text-led until a photo arrives).
- Boat length inconsistency upstream (54' vs 55'): used 55' per FishingBooker + majority of their pages.
- Client contact confirmed: Brian Epstein (user initially misheard the name as Ryan).

## Hotlinking risks
- All images downloaded from the Guidesly CloudFront CDN (dlsmyzcs6vrg4.cloudfront.net) and re-hosted in assets/. Leaving Guidesly will not break this site.

## Reference builds consulted
- JOTL (in full): mixed-tier booking architecture, drawer, form. Big Truck (in full): accordion/JS engineering. See borrowed-patterns.md.

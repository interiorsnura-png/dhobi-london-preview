# Dhobi London V5 — Noindex Public Preview

Date: 22 November 2026

## Changes
- Original design rebuilt into a single static `index.html` with first-party CSS and JavaScript (no Tailwind runtime/CDN)
- Mobile-first conversion path with postcode format validation and official Dhobi booking link
- New dedicated WebP imagery: dry-cleaned suit, white bedding/duvet and hospitality
- Editorial hero, four primary services, smart bundles, heritage, four-step service process, filters and illustrative selection basket, B2B enquiry, areas, FAQs and footer
- No fabricated review ratings or unverified sustainability certifications in newly authored content
- Accessible skip link, native FAQ details, modal semantics and focus trapping, reduced-motion support

## Noindex policy
Keep BOTH `<meta name="robots" content="noindex,nofollow,noarchive">` and `<meta name="googlebot" content="noindex,nofollow,noarchive">` for this public design preview. Do not remove without the client's later instruction. Meta robots do not make the public URL private.

## Operational limitations
- This is a public preview, not a transactional booking integration. The official booking portal is `https://dhobilondon.co.uk/account/`.
- Illustrative rate cards are not approved live pricing. Do not present them as quotes.
- No full-postcode delivery coverage or real-time slot data is available here; the official booking flow is authoritative.
- Location status of Battersea Square and opening times require client confirmation.
- Concept photographs are not photos of the actual Dhobi premises or staff.

## Verification performed
- Browser QA at widths 320, 390, 768, 1440
- No horizontal scrolling; main images tested for display
- Tested invalid postcode, valid postcode, modal, service selection, mobile navigation, pricing filters, basket and official booking link
- No JavaScript runtime errors in interaction test

## Future production launch
Verify trading claims and tariffs, connect CleanCloud for complete data hand-off, add real workshop/team photography, run live mobile Lighthouse/Web Vitals measurements, and revisit noindex only when authorised.
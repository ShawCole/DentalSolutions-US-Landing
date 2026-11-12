# Dental Solutions Puerto Cancún, US landing page

Live: https://dentalsolutions-puertocancun.netlify.app (noindex until the clinic signs off)
Staging: https://dentalsolutions-puertocancun-staging.netlify.app

## How to make changes
- Work on the `staging` branch. Every push to `staging` deploys automatically to the
  staging site within a minute or two. It is a plain static page, so there is no build step:
  edit `index.html`, `assets/` or `fonts/` and push.
- The live site does not deploy from this repo on its own. Once a change is approved on
  staging it is merged into `main` and deployed to the live site.
- Form submissions on staging land in the staging site's Netlify dashboard, not the clinic's.

English, US-facing rebuild of what works on the clinic's paid site (dsc.planetierra.com.mx),
which is Spanish-only and still shows [PENDIENTE]/[VALIDAR] placeholders to the public.

## Kept from their site
- Warm sand, forest green and gold palette with a Cormorant + Manrope type pairing.
- "Least invasive option first" positioning.
- Dr. Carolina's verifiable Mexican professional license (11582421) and named specialist team.
- Six-step concierge journey and per-treatment days-in-Cancún estimates.
- Guided 5-photo virtual pre-assessment with a 24-hour turnaround.
- Deposit policy: cancel with notice and 100% becomes transferable credit for 12 months.
- Warranty tiers: 1 yr composite, 5 yr E-max/zirconia, up to 5 yr implant prosthetics.
- Smile-design quiz that routes into WhatsApp.

## Changed
- English throughout, aimed at US patients. Reference USD prices on every treatment card.
- Quiz now produces a treatment route and a prefilled WhatsApp message.
- Photo form posts to Netlify Forms, with a WhatsApp fallback carrying the visitor's details.
- English testimonial videos from the earlier site, with real poster frames.
- Hero background is the clinic's own Puerto Cancún marina view, not a stock aerial.

## Left out on purpose
- Stock images on their site (laughing man, couple, two veneer "models").
- A travel photo whose filename shows it came from a San Luis Potosí travel agency. Copyright risk.
- Claims still marked [VALIDAR] there: airport pickup, hotel partnerships, transfer costs.

## Needs clinic sign-off before ad traffic
- Warranty durations and the deposit policy are still marked [VALIDAR] on their own site.
- Form submissions land in the Netlify dashboard. Route notifications to the clinic first.
- All-on-4 "from $9,900" is phase one only. The April price list says $12,500 per arch all-in.

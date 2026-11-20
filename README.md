# Supplement Chaser — Demo

**This is a demo, built for design-partner feedback. It is not a launched product, it has no customers, and nothing in it sends a real submission anywhere.**

Collision shops write a supplement on ~95% of repairs, then wait — an average of 4.6 days just for an insurer inspection — while the car sits in a bay and the rental clock runs. Shops that outsource pay ~$145 per supplement for the *writing* (Crash Buddy's published price card) and still submit and chase it themselves, or pay $67K–$130K/yr for an in-house supplement writer. The drafting tools on the market stop at the PDF. Nobody both submits the package and chases the insurer until it pays.

This single-page demo shows that full loop working in a browser:

1. **Intake** — shop, vehicle, insurer, RO #, and the supplement line items found at teardown (pre-filled with one example case; edit anything and the demo updates live).
2. **Package** — one click assembles the submission package: every line checked for photos, an OEM procedure citation, and a match against the carrier estimate, with a readiness verdict and a ready-to-send summary.
3. **Chase** — the automatic follow-up cadence (Day 0 submission, Day 2 status check, Day 4 escalation, Day 7 final notice) written out as real messages referencing the RO #, amount, and days waited, plus a clickable status tracker (Submitted → Acknowledged → Inspection Scheduled → Approved / Short-Paid) and a round-2 dispute draft if the payment comes back short.

## Numbers used (all sourced, nothing invented)

- ~95% of repairs need a supplement — Vermont Department of Financial Regulation autobody study (2026)
- 4.6-day average wait for an insurer in-shop inspection — CRASH Network "Who Pays for What?" survey of 600+ shops
- $145 per supplement outsourced writing cost — Crash Buddy published price card (Nov 2026)
- Supplement review adding more than 7 days to repairs — Vermont DFR finding
- $40,000 recovered in 2 years of short-pay disputes by one Wisconsin shop — Autobody News (Nov 2026)

No customer results, testimonials, or recovered-dollar claims are made for this product — there are no customers yet. The point of the demo is feedback from shops on whether the flow matches their real files.

## Run it

It's one static file — no backend, no build step:

- Live: https://yalakala-naveen.github.io/autobody-supplement-demo/
- Local: open `index.html` in any browser.

## Status

Demo built Nov 20, 2026 by Rembiq (product company) as the wedge for a buyer-first design-partner conversation with collision shops. Next step is shop feedback, not more features.

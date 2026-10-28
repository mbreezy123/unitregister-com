# HANDOFF: Unit Register (unitregister.com)

Shared notes between Matthew's assistant (Chief of Staff, "CoS") and Claude. Whoever edits this repo updates this file before stopping. Newest entry first.

## What this is
Static landing page for Unit Register, a side-project test lane for Matthew Breen (nights only). Audience: HVAC contractors (warranty registration). Hosted on GitHub Pages (repo root = site), custom domain via `CNAME`. Palette: light, brand palette in index.html.

## Status (2026-10-27, 9 PM ET)
- DNS: A/AAAA on root to GitHub Pages and www CNAME to mbreezy123.github.io, set at Porkbun tonight. MX and TXT (Google Workspace mail, SPF, DKIM, DMARC) must never be touched.
- HTTPS: certificate pending at GitHub. CoS enforces HTTPS once issued (a check is scheduled).
- Cold email is live from matt@unitregister.com (Instantly warmup running). The email signature links to https://unitregister.com, so the site must stay up and correct.

## Rules (from Matthew, non-negotiable)
- Light color themes only. No dark themes.
- No fake proof: no made-up charts, metrics, testimonials or "helping similar teams" claims. Sourced numbers only. Sample visuals must be labelled "Sample data, illustrative".
- Must look established and legitimate, not template-like.
- Footer wording: "<Brand>, an independent service operated by Matt Breen", address 14 Prince St, Apt 2E, New York, NY 10012. Phone (650) 954-0304 in signatures.
- Never mention or connect to Gynger (his day job). Nothing here is paid for by or tied to Gynger.
- No LinkedIn and no bots for the nights side business.
- Do not send email, post, or purchase anything. Draft and report instead.
- Keep `CNAME` file as is.

## Division of work
- CoS: Porkbun DNS, Gmail inboxes, Instantly, outreach drafts and sends, GitHub pushes from its box.
- Claude: review and QA (mobile 390px, broken links, accessibility, copy accuracy against cited sources, social preview og.png), and propose or make page fixes via pull request or commit with a note below.

## Open items
- Verify every sourced stat and link on the page (TEFA award, Yardi, etc.); remove anything that cannot be sourced.
- Terms and privacy pages are placeholders and need legal review.
- Re-check og.png and 404 after the logo update.

## Log
- 2026-10-27 CoS: created this file; DNS pointed at GitHub Pages; site unchanged since "Initial site" commit.

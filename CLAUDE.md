# Annie Zhao — portfolio site

Single-page static site (no build step). Currently one HTML file with embedded CSS/JS: `index.html` (formerly `option-a-hover-grid.html` — rename on drop-in).

## Domain & hosting plan
- Domain: **byannie.design** (not yet purchased — buy at Porkbun or Cloudflare Registrar, ~$25–35/yr)
- Hosting: free static hosting — GitHub Pages or Vercel, not yet set up
- Once domain is bought: add a CNAME/A records at the registrar pointing to GitHub Pages, add custom domain in repo settings

## Design direction (locked in)
- Dark theme (`#0B0B0C` bg), oversized display type (Archivo, weight 900), amber accent (`#E8A33D`)
- Persistent left sidebar nav — plain stacked text links (Intro / Work / Background / About / Contact), scrollspy active-state (bold/white for current section, dimmed gray otherwise), modeled on billysweeney.com's nav *mechanic* (not his content)
- Homepage: each of 5 projects is a full-viewport-height section (scroll-snap), styled to read as a big image placeholder (dashed "Project thumbnail" label) — real project images still need to be dropped in
- Background section: work-history list styled as logo circle → company label → **big job title as headline** → date · location meta line → description (also modeled on billysweeney.com's Background section format)
- Click-through / drill-down: full-page takeover (not a small modal), wide image blocks (breaks out to ~1080px) with narrower text column (~620px) for editorial breathing room, modeled on robin-noguier.com's case study page structure. Order: hero image → "01 — Overview" text → image → "02 — Behind the work" panel (role/timeframe/tools facts + "What I wanted to show" / "What I learned" narrative, no named collaborators) → image. Capped at 3 images per project total.

## Content status — placeholder, needs finishing
- All 5 case study descriptions are marked `[Placeholder]` — real copy not written yet
- All project/hero/case-study images are placeholder boxes — no real assets yet
- LinkedIn and Resume links are `href="#"` — need real URLs
- Background section dates for Bloomberg, Jet.com, WePay, Samsung are marked `[dates]` and locations `[location]` — not confirmed, don't guess
- Self-intro copy in the hero is a draft, flagged for revision

## The 5 case studies (fixed scope, in this order)
1. **Boost automation & AI big bets** — lead story, AI in ad-creation flow + how it changed team workflow
2. **Boost on web** — 0-to-1, moved Boost from 0% to ~30% of revenue after Apple's IAP fee
3. **Apple IAP** — payment flow design under Apple's platform constraints
4. **Payments at Meta** — IGBA as hero, Monthly Invoicing as depth, Billing Northstar as closing note
5. **FBR home** — enterprise tools, least fleshed out so far

## Explicit constraints from Annie (don't relitigate without asking)
- No headshot/photo anywhere
- No named collaborators/credits (unlike the Buzz Usborne reference this was inspired by)
- Contact CTA = LinkedIn link
- Max 3 images per project drill-down

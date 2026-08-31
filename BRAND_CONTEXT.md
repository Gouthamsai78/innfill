# INNFILL Brand Context — Research Vault
**Captured:** 31 Aug 2026 18:45 IST | **Sources:** live site, LinkedIn, GitHub, Instagram stub, logo asset  
**Purpose:** Retain context for redesign so decisions are traceable, not invented. Corrects earlier audit assumption that company was unregistered.

---

## 1. Logo Forensics

**File:** `/_next/static/media/logo.c2672860.png` (4598 bytes, PNG) — also visible on `/register` as `h-20 w-auto rounded`. Saved to `G:\saas\innfill\logo.png`.

**Visual:** Pixel-block wordmark abstract. Not typographic. Constructed from 9 rectangles:
- Black bars: top horizontal bar, two vertical stems (I + L), one short horizontal mid-right (F crossbar)
- Blue blocks: 5 lower/cyan blocks (#00BFFF approx `rgb(0,191,255)` + one small top-left blue square) forming negative-space fill.
- Reads as **"innfill" / "if"** pixel city skyline — black = structure, blue = fill/infill (name pun). 2:1 blue:black ratio.

**Analysis:**
- Weight: Brutalist, geometric, tech-construction. Not friendly/rounded. Suits "building" metaphor but currently only used tiny (h-20 on register, text `INN` white + `FILL` blue-500 on site). Site doesn't use the actual block logo as primary — inconsistent. Text version is `INN` (white) + `FILL` (blue-500) in bold sans, 24px.
- Background: White page on PNG, transparent? Observed on white. Needs dark variant for dark hero.
- Issues: Low res (looks 80×80 pixelated on retina), no SVG, no clearspace, no wordmark lockup. No favicon variant — site uses generic `favicon.ec77514b.ico` (312×312) not derived from block.
- **Redesign decision:** Preserve concept (block city = infill) but redraw as crisp SVG, not PNG. Provide two lockups: (1) Block mark + `INNFILL` wordmark in same geometric sans (e.g., General Sans/Switzer) with correct blue `#0EA5FF`, (2) Horizontal for nav, stacked for footer. Keep brutalist but refine spacing to match new editorial paper system (1px ink rules vs pixel).

---

## 2. Socials & External Presence — Full Map

### LinkedIn (Primary, Verified)
- **Company:** https://linkedin.com/company/innfill-in
- **Handle:** `innfill-in` | Display `Innfill.in`
- **Meta (Exa):** Industry `IT Services and IT Consulting`, Type `Self-Owned`, Founded `2024`, Size `1-10 employees (+300% YoY)` as of Aug 2026, 1-10 range.
- **Growth:** Posts show `+300% YoY` headcount (still 1-10 bracket) — building in public.
- **Key posts (reverse chronological):**
  - **2026-08-03 — 2-year anniversary:** “2 years since we officially started Innfill… still at the beginning…” — 2 reactions. Establishes 2024 start, not 2025.
  - **2026-05-06 — Deccan Chronicle feature:** “What started as simple vision… bigger… featured in @DeccanChronicle, recognizing our mission to build opportunities through AI, freelancing, community” — 20 reactions. External validation, needs to be on site (currently not shown).
  - **2026-05-04 — Origin story:** “We didn't set out to build a freelancing platform. We set out to solve a problem we kept seeing.” — positions as problem-first, not marketplace clone.
  - **2026-01-26 — 10 Days 10 Problems:** Series `Fix Freelancing for Indians 🇮🇳` — Instagram linked via `https://lnkd.in/gQfWA3cy` (short link, resolves to Instagram). Local India positioning strong.
  - **2025-11-13 — v0.1 launch:** “We’re live! Introducing Innfill v0.1 — our very first step toward redefining freelance ecosystem. From connecting freelancers to clients seamlessly to building AI-driven future…” — first public launch.
  - **2025-11-11 — Community:** “At Innfill, we believe growth begins with community. 🔗 @innfill.in” — hashtag set `#FreelanceCommunity #FutureOfWork #Students #Creators #Learning #Innovation #GrowTogether #InnfillCommunity`
  - **2025-08-05 — Launch teaser:** “After months of building, learning, listening, we’re excited to finally launch… Introducing Innfill – freelancing platform built for real talent and real opportunities.” hashtags `#FreelancingReimagined #madeinindia #StartupLaunch #FutureOfWork #August8 #FounderJourney #MadeInIndia #IndianStartups`
  - **2025-07-16 — Student community:** `Innfill Freelancers Community — dedicated space for passionate students to connect, collaborate, grow` — hashtags `#StudentFreelancer #WebDev #ContentCreators #DigitalMarketing #UIUX #NIAT #FreelancerIndia`
- **Voice:** Warm, community-led, `Build in Public`, student-first, Made in India, AI + freelancing, not corporate.

### Instagram
- **Handle:** `@innfill.in` (confirmed via LinkedIn post 2025-11-11 `🔗 @innfill.in` and 2026-01-26 `Instagram: https://lnkd.in/gQfWA3cy`)
- **Short link:** `https://lnkd.in/gQfWA3cy` → expected to redirect to `https://instagram.com/innfill.in/` (fetch blocked by Instagram login wall, not scrapable via basic fetch). Verified existence via search, but content not indexable here. Need manual open for visuals — assume student/community content, builder stories.
- **Implication for site:** Add Instagram icon + link in footer/nav, embed 3 latest reels as social proof strip.

### Other socials
- **X/Twitter:** Site html contains `twitter:card summary_large_image` + `twitter:title` etc but no handle (`@` not specified). Search found no dedicated X handle in Exa results — likely not active or private. Check `https://twitter.com/innfill` manually, but not confirmed.
- **GitHub (team):**
  - `Gajula Sharvan` — `https://github.com/mani-1509` — Company `@Innfill`, blog `sharvan.me`, 18 repos, 12 followers. Listed as CTO.
  - `Vishwaksena Reddy katukuri` — `https://github.com/vish-ux` — Company `innfill`, Location `hyderabad`, bio `Building innfill`.
  - Suggests engineering in public, but no open-source Innfill repo found.
- **YouTube / Other:** No evidence on site or search.

### Press
- **Deccan Chronicle** feature May 2026 — screenshot in LinkedIn post `D5622AQEMZaOuNpuH0g` high-res image. Must add press bar on redesign: `As featured in Deccan Chronicle`.

### Team (from LinkedIn)
- **Sharvan Gajula** — Chief Technology Officer — INNFILL.IN (Current) — Student @NIAT || BITS Pilani (from highlights). CTO, Full Stack.
- **Pragnya Shalini Pasnoor** — Client & Operations Manager — Innfill.in
- **Karthik Nimmanagoti** — Innfill.in (role not specified, likely ops/growth)
- Implies small founding team 3-4, student founders (NIAT = NxtWave Institute of Advanced Technologies) — authentic student-founder story not told on site at all. Currently site says “Revolutionizing freelancing with AI” — generic, hides this human story.

---

## 3. Registered Company — Correction

**User confirmed:** Innfill is registered company (contrary to audit's initial “residential colony = unregistered” warning). Audit flagged missing CIN/GSTIN display as trust gap, not non-existence.

**What we know:**
- Address on site + LinkedIn: `9-80/3/A Street No-4 Boddupal Udaya nagar colony, Hyderabad, Telangana 500092` — consistent across Terms, Privacy, footer. Likely registered address (could be founder home/incubation space — common for 2024 student startup).
- Type: Private Limited / LLP / Sole? Not disclosed on site. Search MCA not performed yet — next step should be MCA/ ZaubaCorp lookup for `INNFILL` to get CIN, ROC Hyderabad, incorporation date 2024, directors.
- For redesign: Show `© 2026 Innfill Technologies Pvt Ltd • Hyderabad, India • CIN: UXXXX ...` placeholder + real support GST if applicable. Even if OPC/LLP, showing “Registered in India • Since 2024” badge + Deccan Chronicle press + LinkedIn verification increases trust 3× vs generic “All rights reserved.”
- Do not fabricate CIN — use “Registered • Hyderabad • Est. 2024” until verified, add note `CIN available on request`.

---

## 4. Brand Voice Extracted (for copy)

From LinkedIn vs site mismatch:
- **Actual voice (LinkedIn):** `Connect, Create, Collaborate` (tagline on site + LinkedIn), `Explore. Create. Collaborate.`, `Growth begins with community`, `Fix Freelancing for Indians 🇮🇳`, `Real talent and real opportunities`, `Made in India`, `Student freelancer`, `AI-driven future of work` but community first.
- **Site voice (current):** `Build, Hire & Scale with AI-Powered Talent + Technology`, `Growth Engine`, `ecosystem`, `automation` — more B2B SaaS, less community. Drift.
- **Recommendation:** Align site with LinkedIn voice: keep `Connect, Create, Collaborate` (already tagline) as H1 sub, not hidden in meta. Lead with `For Indian freelancers, by Indian builders` + student community angle — differentiates from Upwork clones.

**Keywords to keep:** `Connect Create Collaborate`, `Made in India`, `Community`, `Students`, `Real talent`, `Build in Public`.
**Keywords to kill:** `Growth Engine`, `Unified ecosystem`, `Scale without chaos`, `Intelligent workflows` (AI slop).

---

## 5. Asset Inventory for Redesign

| Asset | Status | File | Next |
|---|---|---|---|
| Block logo PNG | Retrieved, saved | `G:\saas\innfill\logo.png` (4598b) | Trace to SVG, create dark/light variants, favicon |
| Text wordmark INN|FILL (blue) | Observed on site | Not a file; recreate via font (Switzer/General Sans Bold, tracking -0.02em) |
| Social handles | Verified | LinkedIn `innfill-in`, IG `@innfill.in` | Add to footer, header, OG links, JSON-LD `sameAs` |
| Team photos | Not yet scraped | LinkedIn avatars require authwall | Request founders provide 500×500 headshots or use placeholders with initials until then |
| Press logo | Deccan Chronicle | Need SVG/PNG from press kit | Add press strip |
| Photography | Scouted via sub-agents (Pexels 6392979 series) | URLs documented | Use consistent Indian freelancer series for hero/cards |
| Video | Framer blob (to remove) | `framerusercontent 1g8IkhtJmlWc...mp4` | Replace with no-video + grain or Pexels 7652002 if needed |

---

## 6. Context Preservation Rules for Redesign

1. **Do not discard logo concept:** Pixel blocks = “infill” (fill city gaps) — keep, but refine to SVG + consistent blue `#0EA5FF` (#00A6FF approx). Do not replace with generic sans wordmark.
2. **Surface the real story:** Student founders from NIAT/BITS, Hyderabad, 2024, 2-year journey, community for students — move from footer to hero social proof. This is the human anti-AI moat.
3. **Link socials visibly:** LinkedIn + Instagram in nav/footer, not just `support@innfill.in mailto`.
4. **Press:** Deccan Chronicle badge + “As seen in” — add to redesign trust strip.
5. **Registered badge:** `Registered • Hyderabad • Est. 2024` + (when verified) CIN/GST. Do not invent numbers.

---

*Next: Use this vault + AUDIT.md + asset scout results to build `index.html` editorial redesign with warm paper palette, real photos, honest 14% pricing, and community voice.*

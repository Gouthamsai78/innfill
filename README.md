# Innfill — Freelancing that works for India

Registered Hyderabad marketplace redesign. Warm paper editorial system, Razorpay escrow (14% flat), live pricing calculator, Lenis smooth scroll.

**Live stack:** Single-file `index.html` — Tailwind CDN, Fontshare (Zodiak 600 + General Sans), Google Fonts (Fraunces / JetBrains Mono), Phosphor Icons, Pexels 6392979 Indian freelancer series, shadcn / Preline / Tremor patterns.

## Deploy

### Vercel (recommended) — 30 seconds
1. Go to [vercel.com/new](https://vercel.com/new) → Import `Gouthamsai78/innfill`
2. Framework Preset: **Other** (static) — no build command, output directory `.` (root)
3. Deploy. `vercel.json` handles clean URLs, headers, caching.

Or via CLI:
```bash
npm i -g vercel
vercel --prod
```

### Netlify / Cloudflare Pages
- **Build command:** *(none)*
- **Publish directory:** `.` (or `/`)
- Drag-drop `index.html` + `logo.png` also works.

### Local preview
```bash
npx serve . -l 3000
# or python
python -m http.server 3000
# open http://localhost:3000
```

## Structure
```
index.html                      — main redesign (spacious, Lenis, researched assets)
index-v2.html                   — spacious variant snapshot
index-congested-backup.html     — pre-whitespace backup
logo.png                        — block mark (black + blue infill)
AUDIT.md                        — AI-slop forensic audit
BRAND_CONTEXT.md                — logo + LinkedIn innfill-in + IG @innfill.in + Deccan Chronicle
REDESIGN.md                     — decisions vs Fiverr reference
vercel.json                     — headers + cleanUrls
```

## Notes
- No build step. Tailwind via CDN, Lenis via `unpkg.com/lenis@1.1.20`.
- Respects `prefers-reduced-motion` (Lenis disabled, static poster).
- Photos: Pexels License (William Fortunato series) — free commercial, no attribution required.
- Pricing math per `Terms §6.2`: Service ₹10,000 → Pay ₹10,252 (fee 14% ₹1,400 + GST 18% ₹252) → Freelancer keeps ₹8,600 → Refund ₹9,600 if cancelled early.

# Remortgage Broker Slough — Website Package

This package contains a single-page SEO site targeting the keyword **"Mortgage advisor in Slough"**.

## Files

| File | Purpose |
|---|---|
| `index.html` | The full page — copy, design, and animation, all in one file. |
| `robots.txt` | Tells search engines they can crawl the whole site and points them to the sitemap. |
| `sitemap.xml` | Lists the page URL for search engine indexing. |
| `README.md` | This file. |

## What's inside `index.html`

- **1000+ word article**, semantically structured with one `<h1>`, multiple `<h2>`/`<h3>` headings, an FAQ block, and `FinancialService` schema (JSON-LD) for search engines.
- **One link only**: the anchor text "cubicfinancial" appears once, in the second paragraph of the intro section, linking to `https://www.cubicfinancial.com/`. No other links to that domain exist anywhere else on the page, as requested.
- **No phone number and no call button** anywhere on the page. The contact section uses a simple enquiry form (name, email, message) instead.
- **Solid-color theme** — no gradients anywhere. Palette: deep navy (`#0D2438`), soft paper grey (`#EFF2F0`), and a brass/gold accent (`#B08D3F`).
- **Custom inline SVG illustrations** (house, keys, chart, buildings) instead of stock photos, so the page has no external image dependencies, no licensing risk, and loads fast.
- **GSAP + ScrollTrigger** (loaded from cdnjs) power scroll-based reveals, animated stat counters, a subtle hero parallax, and a header shadow on scroll.
- Fonts: **Fraunces** (headings) + **IBM Plex Sans** (body), loaded from Google Fonts.

## Before you publish

1. **Replace the domain** — swap `https://www.remortgagebrokerslough.com/` in `index.html`, `robots.txt`, and `sitemap.xml` with your real domain.
2. **Update the enquiry form** — it currently only shows a "thanks" message on submit (no backend). Connect it to your email service, a form provider (e.g. Formspree, Netlify Forms), or your CRM.
3. **Add your real business details** — company registration/FCA reference number, registered address, and any regulatory disclosures your compliance team requires for financial promotions.
4. **Review the schema block** at the top of `index.html` (`FinancialService` JSON-LD) and fill in any additional fields (address, opening hours, etc.) once finalized.
5. Re-submit `sitemap.xml` in Google Search Console after upload.

## Notes

- The page is fully responsive down to mobile and uses solid backgrounds throughout (no gradients), per the brief.
- Animations respect standard scroll behavior; if you'd like `prefers-reduced-motion` support added, that's a small addition to the `<script>` block.

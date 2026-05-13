# CLAUDE.md — Blackcurrent Website

Static HTML marketing website for the Blackcurrent brand.

## Files

| File | Purpose |
|---|---|
| `index.html` | Main marketing page — current working version |
| `faq.html` | FAQ page |
| `blackcurrent-website_3.html` | Earlier iteration — reference only |

No build step. Open directly in a browser or serve with:
```bash
python3 -m http.server 8080
```

## Design system

All styles are inline in each HTML file. No external stylesheet.

**Fonts:** Inter (Google Fonts) — weights 400, 500, 700, 800

**CSS variables:**
```css
--rust: #ec5f30          /* primary CTA and accent colour */
--rust-dark: #c44a20     /* hover state */
--charcoal: #22201d      /* nav, hero, dark backgrounds */
--charcoal-soft: #2e2b27
--egg: #fffaef           /* page background */
--white: #ffffff
--sapphire: #5597d1      /* secondary accent */
--steel: #a2a09e         /* body text on dark */
--lead: #3a3a3a
```

**Layout:** `--section-pad: clamp(4rem, 8vw, 7rem) clamp(1.5rem, 6vw, 6rem)`

## Page sections (index.html)

| Section ID | Label |
|---|---|
| `#hero` | Hero |
| `#problem` | The Problem |
| `#opportunity` | The Opportunity |
| `#difference` | The Blackcurrent Difference |
| `#flex` | Flex Platform |
| `#value` | Value in Action |
| `#how-it-works` | How It Works |
| `#trust` | Why Businesses Trust Us |
| `#cta` | CTA |

## Brand context

Load before any copy or design changes:
- `../../_brand/blackcurrent_master_prompt.md`
- `../../_brand/blackcurrent_brand_guidelines.md`

**Language:** Australian English — *optimise*, *organisation*, *programme*
**Tone:** Commercially credible, plain-language. Not informal, not legalistic.
**Tagline:** "Solar That Works Harder"

## Assets in this directory

- `BC Brand Guidelines Oct 2025.pdf` — full brand guidelines (print reference)
- `Screenshot *.png` — Flex platform UI screenshots (used in Flex Platform section)
- `Flex_Website_Brief.docx` — original website brief

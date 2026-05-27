---
title: Typography
description: The ELIXIR-UK type system – Lato primary, Open Sans fallback, Merriweather for editorial print titles. Type scale for web and print.
page_id: typography
type: brand
resources: [font-lato, font-open-sans, font-merriweather]
related_pages:
  brand:
    - colour
    - logos
  style_guide:
    - accessibility
---

ELIXIR-UK uses **Lato** everywhere – body, UI, headings, footers, social, slides. **Open Sans** is the fallback when Lato isn't available (e.g., older Word installs, certain platforms). **Merriweather** is a serif used only for titles on editorial prints (reports, posters, formal documents). That's it – three roles, narrow lanes, no other typefaces.

## Lato – primary

Used for everything by default. Body, headings, UI, navigation, captions, the footer, social cards, slide decks.

<div style="font-family: 'Lato', sans-serif; padding: 24px; background: #FFFFFF; border: 1px solid #DDE3E7; border-radius: 0.3rem; margin: 1rem 0;">
  <div style="font-weight: 700; font-size: 2rem; color: #023452; line-height: 1.2;">Lato Bold 32</div>
  <div style="font-weight: 700; font-size: 1.25rem; color: #023452; margin-top: 0.5rem;">Lato Bold 20</div>
  <div style="font-weight: 600; font-size: 1rem; color: #023452; margin-top: 0.75rem;">Lato Semibold 16</div>
  <div style="font-weight: 400; font-size: 1rem; color: #001F33; margin-top: 0.75rem;">Lato Regular 16 – the body weight. Open counters, neutral tone, reads well at 14-18px on screen and in print.</div>
  <div style="font-weight: 300; font-size: 0.875rem; color: #4A6577; margin-top: 0.75rem;">Lato Light 14 – use only above 14px and only for subtitles, never body.</div>
</div>

Why Lato: clean, modern, friendly. Broad weight range (100 → 900). Designed for screen but works in print. Free under the Open Font License.

## Open Sans – fallback

Used when Lato isn't available – an older Word install, certain email clients, a presentation template that doesn't ship Lato. Visually close enough to Lato that a document partially set in each won't jar. **Never used by choice** – Lato is the default whenever it's an option.

<div style="font-family: 'Open Sans', sans-serif; padding: 24px; background: #FFFFFF; border: 1px solid #DDE3E7; border-radius: 0.3rem; margin: 1rem 0;">
  <div style="font-weight: 700; font-size: 1.5rem; color: #023452; line-height: 1.2;">Open Sans Bold 24</div>
  <div style="font-weight: 400; font-size: 1rem; color: #001F33; margin-top: 0.75rem;">Open Sans Regular 16. The Lato-fallback. If you find yourself setting a document in Open Sans by choice, check whether Lato is actually unavailable first.</div>
</div>

## Merriweather – editorial titles in print

A serif. Used **only** for titles in editorial prints – annual reports, posters, formal documents, event programmes. Never for body, never for web pages, never for headings outside print.

<div style="font-family: 'Merriweather', serif; padding: 24px; background: #FFFFFF; border: 1px solid #DDE3E7; border-radius: 0.3rem; margin: 1rem 0;">
  <div style="font-weight: 700; font-size: 2rem; color: #023452; line-height: 1.2;">Merriweather Bold 32</div>
  <div style="font-weight: 400; font-size: 1.125rem; color: #4A6577; margin-top: 0.5rem; font-style: italic;">– used for editorial print titles, sparingly</div>
</div>

Why Merriweather: warm editorial serif designed for screen and print, with broad weight range. Pairs cleanly with Lato (both humanist proportions). Free under the Open Font License.

## Type scale

Web and print have different defaults. Web body sits at 16 px for accessibility and screen readability; print body sits at 10.5–11 pt because reading distance is closer and the dpi is higher. Use the column that matches your medium.

| Level | Use | Web (rem / px) | Print (pt) |
|---|---|---|---|
| H1 | Page or document title | 2 rem / 32 px | 24–28 pt |
| H2 | Section heading | 1.5 rem / 24 px | 18 pt |
| H3 | Sub-section | 1.25 rem / 20 px | 14 pt |
| H4 | Block heading | 1.125 rem / 18 px | 12 pt |
| Body | Paragraph text | 1 rem / 16 px | 10.5–11 pt |
| Small | Captions, meta, footer | 0.875 rem / 14 px | 9 pt |
| Tiny | Legal, footnotes, badges | 0.75 rem / 12 px | 8 pt |

The scale is a default, not a straitjacket. Stick to it when nothing in the design pushes against it; step in or out when a specific context genuinely needs a different size.

## Hierarchy in practice

A sample of the hierarchy on a typical page.

<div style="font-family: 'Lato', sans-serif; padding: 32px; background: #FFFFFF; border: 1px solid #DDE3E7; border-radius: 0.3rem; margin: 1rem 0;">
  <div style="font-weight: 400; font-size: 0.8125rem; color: #4A6577; letter-spacing: 0.16em; text-transform: uppercase; padding-bottom: 0.75rem; border-bottom: 1px solid #DDE3E7; margin-bottom: 1rem;">BRAND</div>
  <h1 style="font-weight: 700; font-size: 2.5rem; color: #023452; margin: 0 0 1.5rem;">Page title</h1>
  <h2 style="font-weight: 700; font-size: 1.75rem; color: #023452; margin: 0 0 0.75rem;">A section heading</h2>
  <p style="font-weight: 400; font-size: 1rem; color: #001F33; line-height: 1.55; margin: 0 0 1rem;">Body paragraph in Lato Regular 16. Comfortable reading length sits at around 60 to 75 characters per line; longer than that and the eye loses track between lines.</p>
  <h3 style="font-weight: 700; font-size: 1.375rem; color: #023452; margin: 1rem 0 0.5rem;">A subsection</h3>
  <p style="font-weight: 400; font-size: 1rem; color: #001F33; line-height: 1.55; margin: 0 0 0.75rem;">More body text. Hierarchy comes from <strong style="font-weight: 700;">weight and size</strong>, not from colour shifts.</p>
  <p style="font-weight: 400; font-size: 0.875rem; color: #4A6577; margin: 0;">A caption in Small / Slate – metadata, attribution, photo credits.</p>
</div>

## Weights

Use the weights below; don't reach for others.

| Weight | Use |
|---|---|
| 700 (Bold) | Headings, strong emphasis |
| 600 (Semibold) | UI labels, sub-headings, buttons |
| 400 (Regular) | Body text |
| 400 Italic | Pull quotes, terminology, scare quotes |
| 300 (Light) | Display sub-titles only (above 14 px), never body |

Italic is for genuine emphasis or quoted phrases – don't italicise whole paragraphs. Bold is for true emphasis – don't use it as decoration.

## Line length and leading

- **Body text:** aim for 60–75 characters per line. Beyond that the eye loses track between lines.
- **Line-height (leading):**
  - Body: 1.5–1.6 × the font size.
  - Headings: 1.2–1.3 × the font size – tighter than body.
  - Captions: 1.4 × the font size.
- **Margins between paragraphs:** 0.75–1 rem. Spacing between paragraphs does as much work as font size in establishing rhythm.

## Don't

- **Don't introduce other typefaces.** No Arial, Helvetica, Calibri, Georgia, Times New Roman, Roboto. Lato (or Open Sans as a fallback) covers every screen and most print needs; Merriweather covers editorial print titles. That's the set.
- **Don't reach for Open Sans by choice.** It's the fallback for when Lato isn't available – not a parallel face. If you can use Lato, use it.
- **Don't use Merriweather outside editorial print titles.** Not on the web, not for body, not for slide headings. Print titles only.
- **Don't set body in light or thin weights.** Below 400 weight, body text is hard to read at small sizes – fails accessibility and looks pretentious.
- **Don't set body in all caps.** Reading caps is slow; comprehension drops. Caps are for labels, badges and short eyebrow text only.
- **Don't justify body text.** Left-aligned, ragged-right reads more comfortably and avoids the "rivers" that justified paragraphs create.
- **Don't underline non-link text.** Underlines on the web mean "this is a link". Use bold or italic for emphasis instead. See [Accessibility]({{ '/accessibility' | relative_url }}).
- **Don't squeeze the type scale.** If a heading is feeling cramped, give it more space rather than dropping its size below the next scale step.


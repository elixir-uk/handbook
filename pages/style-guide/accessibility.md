---
title: Accessibility
description: What every contributor needs to do – in writing and in structure – to meet WCAG 2.2 AA and work for screen readers, keyboard navigation and assistive software.
page_id: accessibility
type: style_guide
---

ELIXIR-UK writes for researchers, research technical professionals, students, funders and – to some extent – the public. That audience spans the full range of abilities. This page covers what every contributor needs to do – in writing and in structure – to make sure our content works for everyone, including people using screen readers, keyboard navigation or assistive software.

{% include callout.html type="important" content="**We target WCAG 2.2 Level AA.** That is the level expected of UK public-sector and publicly-funded content under the [Public Sector Bodies Accessibility Regulations](https://www.gov.uk/guidance/accessibility-requirements-for-public-sector-websites-and-apps). When in doubt, default to the more accessible option." %}

## Plain English

Accessible writing is plain writing. Short sentences. Common words. Jargon explained on first use. Avoid metaphors that depend on shared cultural reference.

- See [Voice]({{ '/voice' | relative_url }}) for the voice principles – they double as accessibility principles.
- See [Conventions]({{ '/conventions' | relative_url }}) for British English spelling and acronym handling.

If a sentence makes you stumble when read aloud, it will be harder still for someone using a screen reader.

## Headings and structure

Headings are the scaffolding screen readers use to navigate. Use them properly.

- **One H1 per page.** Set automatically by the page title.
- **H2 for top-level sections, H3 for subsections, H4 for sub-subsections.** Don't skip levels (no H2 → H4).
- **Headings describe what is below them.** Not decorative, not clickbait. *"How to use this page"* beats *"Read me first!"*.
- Sentence case (see [Conventions]({{ '/conventions' | relative_url }})).
- Short – aim for a phrase that fits on one line.

## Link text

The link text is what a screen reader announces when it lands on the link. It is also what users see in a generated "list of links on this page" view. Make sure each link makes sense on its own.

- The whole verbal phrase is the link, not "click here" at the end of the sentence.
- See [Writing a webstory → Linking]({{ '/writing-a-webstory#linking' | relative_url }}) for the full rules.

✓ [Read the published article](#)

✗ To read the published article [click here](#)

## Images and alt text

- **Every meaningful image needs alt text.** Describe what the image conveys in context, not the literal pixels.
- **Decorative images get empty alt** (`alt=""`). Don't waste a screen-reader user's time describing a flourish.
- **Don't repeat the caption** in the alt text – they serve different readers.
- See [Writing a webstory → Banner image and alt text]({{ '/writing-a-webstory#banner-image-and-alt-text' | relative_url }}) for examples.

## Inclusive language

Words shape who feels included. A few rules of thumb:

| Default to | Avoid | Why |
|---|---|---|
| **People with disabilities** / **disabled people** | "the disabled", "the handicapped" | Both forms (person-first and identity-first) are accepted; "the disabled" is not. Match the community's preference when known. |
| **Everyone**, **the team**, **folks** | "guys" | "Guys" reads as male-default to some readers, especially in formal contexts. |
| **Chair**, **spokesperson**, **firefighter** | "chairman", "spokesman", "fireman" | Drop unnecessary gendering. |
| **Blocklist** / **allowlist** | "blacklist" / "whitelist" | The colour-coded version carries unintended baggage. Industry has largely moved on. |

When referring to a person, default to their stated pronouns. When pronouns aren't known, use **they/them** rather than guessing.

## Tables

- Tables need a header row. Screen readers use the header to announce each cell ("Term: ELIXIR-UK; Use it for: standard short form").
- Don't use tables to lay out non-tabular content. If it's a side-by-side comparison or a list with multiple attributes, a table is right. If it's just text in columns for visual effect, use prose.
- Keep tables short. If a table grows past ~15 rows, consider breaking it up by category.

## Multimedia

- **Videos** need captions. Auto-generated captions from YouTube are a starting point, not a finished product – review and correct.
- **Audio** (podcasts, recorded talks) needs a written transcript.
- **Embeds** (slides, demos) need a text alternative or a description of what's in them.

## Colour and visual accessibility

This is largely a brand/design concern – see the [Brand]({{ '/brand' | relative_url }}) section.

Two writing-side rules that touch on visual accessibility:

- **Never communicate with colour alone.** Pair colour with a symbol, a label or a tag, so the meaning still lands for readers who can't distinguish the colour.
- **Links must be underlined**, not just coloured. A coloured-only link is invisible to readers with colour vision deficiencies.
- **No images of text.** If the words are important, put them in real text, not baked into an image (the screen reader can't read them and the user can't enlarge them).

## Testing your work

Quick checks every contributor can do before publishing:

1. **Read it aloud.** If you stumble, it's too complex. Rewrite.
2. **Tab through the page with the keyboard.** Every link, button and form field should be reachable. The focus indicator should be visible.
3. **Check contrast** of any custom-coloured text against its background using [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/). Target AA: 4.5:1 for normal text, 3:1 for large text.
4. **Open the browser's accessibility tab.** Chrome DevTools → Lighthouse → Accessibility. Firefox → Accessibility Inspector. Safari → Audit. These won't catch everything but they catch common mistakes.

## Quick checklist before publishing a webstory

- One H1 (set by the title). H2s and H3s in order, no skips.
- Alt text on every meaningful image. Decorative images have empty alt.
- Link text describes the destination. No "click here".
- No images of text.
- No colour-only meaning.
- Plain English. Read aloud, then tighten.
- Captions on any video. Transcript for any audio.

## If you find something inaccessible on the live site

Email [contact@elixiruknode.org](mailto:contact@elixiruknode.org) with the URL and a description of the issue. Accessibility bugs are bugs – they get fixed, not deprioritised.

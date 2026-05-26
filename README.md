# ELIXIR-UK Handbook

A Jekyll site that documents the ELIXIR-UK brand, voice, communications strategy, and community participation model — and doubles as an LLM system prompt for on-brand drafting.

Source for the [published site](https://elixir-uk.github.io/style-guide/) _(once deployed)_.

## What's here

- **Brand** — visual identity: logos, colour, typography, imagery, templates
- **Style guide** — how we write: voice, lexicon, do-and-don't, LLM system prompt
- **Communications strategy** — OASIS framework: objectives, audiences, channels, implementation, evaluation, crisis comms
- **Community participation model** — participation guidelines (code of conduct), who the community is, pathways, engagement, governance

## How to edit

The whole site is markdown. Find the page you want to change in `pages/`, edit the `.md` file, push to `main`. The GitHub Actions workflow builds and deploys to GitHub Pages on every push to `main`.

## Running locally

Requires Ruby 3.3+ and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Theme

This site uses the [ELIXIR Toolkit Theme](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme) (`v6.0.0`), the same theme used by RDMkit, WorkflowHub, RO-crate, and 20+ other ELIXIR projects. It's loaded via `remote_theme:` in `_config.yml`, so the theme stays up-to-date without us forking it.

## How the LLM-prompt workflow works

The voice & tone section is authored as plain markdown so it can be consumed two ways:

1. **Humans read the rendered site** at the published URL.
2. **An LLM consumes the markdown directly** — paste the prompt from `pages/voice-and-tone/llm-system-prompt.md` into Claude / ChatGPT / Gemini as a system prompt to get on-brand drafts.

The principle: **one source, two readers.** Update the voice/lexicon/examples pages, then sync the `llm-system-prompt.md` from them. Never maintain a separate "prompt document" that drifts from the public guidelines.

## Deployment

GitHub Pages, built via GitHub Actions (`.github/workflows/jekyll.yml`). To enable:

1. Push this repo to GitHub.
2. Settings → Pages → set Source to "GitHub Actions".
3. Push to `main` — the workflow builds and deploys.

## Status

Bootstrap scaffold (May 2026). Section pages are stubbed; content authoring in progress. The original brand guidelines PDF was lost when Adobe Cloud was deprecated; rebuilding from memory + the one surviving page + the parent ELIXIR Europe brand references.

## Contributing

Open a pull request. Small fixes (typos, clarifications) can be merged directly. Voice and brand-rule changes should pin in `@xenia` for review.

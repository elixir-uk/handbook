# ELIXIR-UK Handbook

A Jekyll site that documents the ELIXIR-UK brand, voice and communications strategy – and doubles as an LLM system prompt for on-brand drafting.

Source for the [published site](https://elixir-uk.github.io/handbook/).

## What's here

- **Brand** – visual identity: logos, colour, typography, imagery, templates
- **Style guide** – how we write: voice, conventions, do-and-don't, writing for webstories and social, LLM system prompt
- **Communications strategy** – OASIS framework: objectives, audiences, strategy, implementation, evaluation, crisis comms

## How to edit

The whole site is markdown. Find the page in `pages/`, edit the `.md` file, push to `main`. The GitHub Actions workflow builds and deploys to GitHub Pages on every push.

## How to add or update a resource

1. Drop the file in the right `assets/` subfolder via a pull request.
2. Register it in `_data/tool_and_resource_list.yml` with: `id`, `name`, `url`, `description`, `type`, `section: [list]`. A resource can belong to more than one section.
3. To show the resource at the bottom of a specific page, add the resource's `id` to that page's `resources: [...]` frontmatter list.
4. The resource will also appear automatically on the [Templates](pages/brand/templates.md) page under every section in its `section:` list – no separate edit needed.

## How the LLM-prompt workflow works

The style guide is authored as plain markdown so it can be consumed two ways:

1. **Humans read the rendered site** at the published URL.
2. **An LLM consumes the markdown directly** – point it at `pages/style-guide/llm-system-prompt.md` (or the published version) to get on-brand drafts.

**One source, two readers.** Update the voice / conventions / examples pages directly; never maintain a separate "prompt document" that drifts from the public guidelines.

## Theme

This site uses the [ELIXIR Toolkit Theme](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme) (`v6.0.0`), shared with RDMkit, WorkflowHub, RO-crate and 20+ other ELIXIR projects. Loaded via `remote_theme:` in `_config.yml`.

For local setup, forking and deployment, callouts, sidebars, navigation tiles and other theme features, see the [ETT documentation](https://elixir-belgium.github.io/elixir-toolkit-theme/).

## Contributing

Open a pull request. Small fixes (typos, clarifications) can be merged directly. Voice and brand-rule changes should pin in `@xenia` for review.

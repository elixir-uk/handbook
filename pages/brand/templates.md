---
title: Templates & downloads
description: Working files — logos, document templates, fonts, and the external resources ELIXIR-UK inherits from.
page_id: templates
resources: [main-logo-horizontal, main-logo-mark, logo-sponsored, logo-expanded, tpl-letterhead, tpl-slide-deck, tpl-social-post, tpl-webstory-hero, tpl-event-announcement, font-lato, font-source-serif, font-work-sans, elixir-hub, elixir-uk-website, elitma, rdmkit, ds-handbook, workflowhub, steers-comms-toolkit, elixir-brand-guidelines, elixir-style-guide]
---

Everything you need to make something on-brand: logos, document templates, fonts, and the external resources we inherit from.

The table below is the single source of truth. Each row's "Related pages" column lists where the resource is used or referenced across this guide. Sort or search the table directly.

## How to add or update a file

1. Drop the file in `assets/img/logos/` (or another suitable `assets/` subfolder) via a pull request to [the repo](https://github.com/elixir-uk/style-guide).
2. Register it in [`_data/tool_and_resource_list.yml`](https://github.com/elixir-uk/style-guide/blob/main/_data/tool_and_resource_list.yml) with an `id`, `name`, `url`, `description`, and `category` (`template` / `external_resource` / `internal_resource`).
3. Reference it from any page's frontmatter via `resources: [your-new-id]` — it will appear in that page's "Tools and resources" section, and the page will appear in this table's "Related pages" column for that row.

{% include resource-table-all.html %}

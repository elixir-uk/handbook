---
title: Templates & downloads
description: Working files – logos, document templates, fonts, imagery and the external resources ELIXIR-UK inherits from.
page_id: templates
type: brand
---

Everything you need to make something on-brand, grouped by which section of the handbook the resource belongs to. A resource can appear in more than one section.

## How to add or update a resource

1. Drop the file in the right `assets/` subfolder via a pull request to [the repo](https://github.com/elixir-uk/style-guide).
2. Register it in [`_data/tool_and_resource_list.yml`](https://github.com/elixir-uk/style-guide/blob/main/_data/tool_and_resource_list.yml) with: `id`, `name`, `url`, `description`, `type`, `section: [list]` (a resource can belong to more than one section), and `related_pages: [list of page-ids]` (which pages should auto-display this resource at the bottom).
3. **To show the resource at the bottom of a specific page**, add the page's `page_id:` value into the resource's `related_pages` list in the YAML. Make sure the page itself has `page_id: that-slug` in its frontmatter. The theme will auto-render a resource table on that page.
4. **It will appear here automatically** under every section listed in its `section:` list – no separate edit needed on this page.

{% include resource-table-all.html section="brand" heading="Brand" heading_level="h2" %}

{% include resource-table-all.html section="style-guide" heading="Style guide" heading_level="h2" %}

{% include resource-table-all.html section="communications-strategy" heading="Communications strategy" heading_level="h2" %}

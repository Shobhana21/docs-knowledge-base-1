Content tools in Document360 give you the building blocks to manage, reuse, and organize documentation content at scale. Instead of duplicating information across articles or updating the same content in multiple places every time something changes, content tools let you centralize reusable elements, attach structured metadata, and apply bulk operations across your entire knowledge base.

Content tools are grouped into two areas: **content reuse** and **metadata & organization**.

---

## Why use content tools

As a knowledge base grows, maintaining consistency becomes a significant challenge. The same product name appears in dozens of articles. A legal disclaimer is copy-pasted across multiple pages. A glossary term is defined differently depending on who wrote the article. Any one of these can erode reader trust and create maintenance overhead that compounds over time.

Content tools address this directly:

- **Consistency** — Variables and snippets ensure the same information renders identically across every article that uses it. Changing the source updates all instances at once.
- **Reduced maintenance** — Instead of hunting through articles to update repeated content, you edit once and the change propagates automatically.
- **Faster authoring** — Writers insert predefined variables, snippets, and glossary terms rather than retyping or copying content from another article.
- **Better organization** — Custom fields let teams attach structured metadata — version numbers, owners, review dates — to articles, making large documentation sets easier to audit and manage.
- **Reader experience** — Glossary terms give readers on-demand definitions without sending them away from the page they are reading.

---

## Content reuse

Content reuse tools let you define content once and use it across as many articles as needed. When the source changes, every instance updates automatically — no manual find-and-replace required.

Use content reuse when the same information appears in multiple articles, when terminology needs to be consistent across your knowledge base, or when shared content (such as a legal disclaimer or a support contact block) is subject to periodic updates.

<div class="doc360-card-row">
  <div class="doc360-card">
    <div class="doc360-card__header">
      <p class="doc360-card__title">Variables</p>
    </div>
    <p class="doc360-card__desc">Reusable text values — product names, version numbers, contact details, or short phrases — that update everywhere they are used when you edit the source.</p>
    <a href="https://docs.document360.com/docs/variables" class="doc360-card__link">Learn more →</a>
  </div>
  <div class="doc360-card">
    <div class="doc360-card__header">
      <p class="doc360-card__title">Snippets</p>
    </div>
    <p class="doc360-card__desc">Reusable content blocks — paragraphs, tables, callouts, images, or code — that render as regular article content and update across all articles when edited.</p>
    <a href="https://docs.document360.com/docs/snippets-1" class="doc360-card__link">Learn more →</a>
  </div>
  <div class="doc360-card">
    <div class="doc360-card__header">
      <p class="doc360-card__title">Glossary</p>
    </div>
    <p class="doc360-card__desc">Defined terms that appear as dotted-underlined text in articles. Readers hover over a term to view its definition without leaving the page.</p>
    <a href="https://docs.document360.com/docs/glossary" class="doc360-card__link">Learn more →</a>
  </div>
</div>

---

## Metadata & organisation

Metadata tools let you attach structured, searchable information to articles beyond the default fields — helping teams organise content, enforce governance, and make documentation easier to manage at scale.

Use metadata tools when your team needs to track information such as product version, content owner, review status, or release stage across a large number of articles. Metadata can also power integrations and API-driven workflows that require structured data from your knowledge base.

<div class="doc360-card-row">
  <div class="doc360-card">
    <div class="doc360-card__header">
      <p class="doc360-card__title">Custom fields</p>
    </div>
    <p class="doc360-card__desc">Define your own fields — text, dropdowns, dates, booleans, and more — and attach them to articles, category pages, and decision trees to capture structured information specific to your team's workflow.</p>
    <a href="https://docs.document360.com/docs/custom-fields" class="doc360-card__link">Learn more →</a>
  </div>
</div>

---

## Best practices

- **Match the tool to the content type** — Use variables for short, frequently changed text values. Use snippets for formatted blocks that include structure or media. Use the glossary for terms that need reader-facing definitions. Mixing these up (for example, putting a paragraph in a variable) leads to maintenance issues.
- **Establish naming conventions before you scale** — Set a consistent naming pattern for variables, snippets, and glossary terms before your team creates dozens of them. For example, prefix snippet names with the content type: `[Warning] Unsaved changes` or `[Contact] Support block`. This keeps the library scannable.
- **Audit usage before deleting** — Always check the **Used in** column before deleting a variable, snippet, or glossary term. Deleting content that is actively referenced in published articles removes it from those articles immediately.
- **Use custom fields for governance, not content** — Custom fields are designed for structured metadata (owner, version, review date), not for storing article content. Keep field values concise and consistent so they are useful for filtering and reporting.
- **Translate reusable content alongside articles** — If your project supports multiple languages, translate variables, snippets, and glossary terms as part of the same workflow as the articles that use them. Publishing an article in French while its variables are only in English will surface the English value to French readers.

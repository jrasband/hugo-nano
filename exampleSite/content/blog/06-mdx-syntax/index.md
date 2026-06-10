---
title: "Markdown and Shortcode syntax guide"
description: "Get started writing content in Hugo using markdown and shortcodes."
date: "2024-03-16"
---

Hugo uses Goldmark as its default Markdown parser. It is extremely fast, compliant with CommonMark, and supports custom extensions like tables, task lists, and auto-linked references.

Unlike Astro, which uses MDX to import component files directly, Hugo leverages **Shortcodes** to inject dynamic HTML or templates directly into your markdown.

---

### Example 1: Standard Hugo Shortcodes

Hugo comes with built-in shortcodes for embedding YouTube videos, Instagram posts, Twitter tweets, and Gists.

`{{</* githubmap */>}}`

---

### Example 2: Creating Custom Shortcodes

You can easily create custom shortcodes by placing HTML files in `layouts/partials/` or `layouts/shortcodes/`. For example, a custom button shortcode (`layouts/shortcodes/button.html`) can be defined as:

```html
<a href="{{ .Get "url" }}" class="button">
  {{ .Get "text" }}
</a>
```

And used in your markdown:

`{{</* button url="https://gohugo.io" text="Learn Hugo" */>}}`

---

### More Links
- [Hugo Shortcodes Documentation](https://gohugo.io/content-management/shortcodes/)
- [Goldmark Markdown Configuration](https://gohugo.io/getting-started/configuration-markup/)
- [Hugo Directory Layout guide](https://gohugo.io/getting-started/directory-structure/)

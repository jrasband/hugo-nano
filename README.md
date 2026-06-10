# Hugo Nano

Hugo Nano is a static, minimalist, lightweight, and lightning-fast portfolio and blog theme. It is migrated from the popular Astro Nano template, designed to have zero dependencies, zero heavy JS frameworks, and a completely clean and readable codebase.

## 📋 Features

- **Minimalist Design**: Clean typography and layouts focused on readability.
- **Responsive Layout**: Works beautifully on mobile, tablet, and desktop screens.
- **Accessibility & SEO**: Built with semantic HTML, single-h1 hierarchy, and fully responsive layouts.
- **Light/Dark/System Theme**: Instant theme toggles with CSS Custom Properties.
- **Polished Animations**: Smooth scroll-based fade-in effects and micro-animations on cards and buttons.
- **No Heavy Frameworks**: No Tailwind or node modules — styled with modular plain CSS.
- **Performance Optimized**: Assets (CSS and JS) are minified and fingerprinted automatically using Hugo Pipes.
- **RSS & Sitemap**: Natively auto-generated feeds out of the box.

---

## 🚀 Getting Started

### Installation

To use this theme in your Hugo site, you can add it as a git submodule:

```bash
# From the root of your Hugo site directory:
git submodule add https://github.com/jrasband/hugo-nano.git themes/hugo-nano
```

Or, if you use Hugo Modules, add it to your `hugo.toml`:

```toml
[module]
  [[module.imports]]
    path = "github.com/jrasband/hugo-nano"
```

### Configuration

Add the theme name to your site's configuration file:

```toml
theme = "hugo-nano"
```

You can view [exampleSite/hugo.toml](exampleSite/hugo.toml) for a complete example of configuration parameters including socials, navigation counts, and home settings.

---

## 💻 Local Development

To run the example site locally:

1. Navigate to the `exampleSite` folder:
   ```bash
   cd exampleSite
   ```
2. Start the Hugo server:
   ```bash
   hugo server
   ```

To build a static version of the example site:
```bash
hugo -s exampleSite
```

---

## 🏛️ License

MIT License.
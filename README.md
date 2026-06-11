# Hugo Nano

Hugo Nano is a static, minimal, and fast portfolio and blog theme. It is a
[hugo](https://gohugo.io/) port of the [Astro Nano
template](https://github.com/markhorn-dev/astro-nano).

---

## Quickstart

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

See [exampleSite/hugo.toml](exampleSite/hugo.toml) for an example of configuration parameters.

---

### Preview example site

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

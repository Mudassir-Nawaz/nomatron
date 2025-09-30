# Nomatron Hugo Theme

Nomatron is a custom Hugo theme built with TailwindCSS.  
This repository contains the theme itself along with an example site to help you get started.

---

# Prerequisites
To start using this template, you need to have some prerequisites installed on your machine.

- Hugo Extended v0.150+
- Node v22+

---

## Installation

1. Add the theme to your Hugo site.

2. Enable the theme in your site configuration (`config.toml`):

   ```toml
   theme = "nomatron"
   ```

3. Run your site locally:

   ```bash
   hugo server -D
   ```

   The site will be available at `http://localhost:1313`.

---

## Example Site

This theme includes an example site located at:

```
themes/nomatron/exampleSite/
```

To run the example site:

```bash
cd themes/nomatron/exampleSite/
hugo server
```

The example site includes:

- A `config.toml` with minimal configuration
- Sample content under `content/`
- Example pages to demonstrate the theme

---

## Configuration

You can customize your site using Hugo’s configuration file.  
Example `config.toml`:

```toml
baseURL = "https://example.com/"
languageCode = "en-us"
title = "My Hugo Site"
theme = "nomatron"

[params]
  theme_switcher = true
```

---

## Content

Add your content to the `content/` directory of your site. For example:

```
content/_index.md
content/posts/first-post.md
```

Example `posts/first-post.md`:

```markdown
---
title: "First Post"
date: 2025-09-30
---

This is my first post using the Nomatron theme.
```

---

## License

This theme is released under a Proprietary license.  
See the `theme.toml` file for details.
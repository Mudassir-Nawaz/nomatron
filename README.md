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

3. Copy sampleSite files to your site.

4. Run your site locally:

   ```bash
   hugo server -D
   ```

   The site will be available at `http://localhost:1313`.

---

## Configuration

You can customize your site using Hugo’s configuration file.  
Example `config.toml`:

```toml
baseURL = 'https://example.org/'
languageCode = 'en-US'
title = 'My New Hugo Site'


########## Menus
[menus]
  ########## Main/Header
  [[menus.main]]
    name = 'Home'
    pageRef = '/'
    weight = 10
```

---

## Content

Add your content to the `content/` directory of your site. For example:

```
content/_index.md
```

Example `about.md`:

```markdown
---
title: About Us
description: Lorem ipsum dolor sit amet consectetur adipisicing elit.
---
```

---

## License

This theme is released under a Proprietary license.  
See the `theme.toml` file for details.
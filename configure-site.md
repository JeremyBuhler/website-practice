---
title: "Configure site"
nav_order: 2
---


## Configuring your site

Site-wide configuration settings are in a file named `_config.yml`. There are many possible settings, but a `_config.yml` file for a simple site migth look like this:

```yaml
title: Example site title 
description: A short description of the site
theme: minima
```
> [!TIP]
> View the .md file for this page to see how to display code content with appropriate syntax highlight (in this case, _yaml_), and how to format a "tip" callout like this one! See more about callouts [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts).  


### Set a theme

GitHub Pages supports more than a dozen themes. To switch to any of these themes, update the `theme: minima` line in `_config.yml` and replace "minima" with a theme from [this list](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll#supported-themes).


### Page-level settings 

Configuration for individual pages is set in a specially formatted block at the top of each page file, referred to as the _yaml front matter_. Here's the front matter for this page:

```yaml
---
title: "Configure site"
nav_order: 2
---
```

The yaml front matter block can be as long as needed, and there are many other useful settings. For example:

- `nav_exclude: true` excludes the page from the navigation menu
- Set page hierarchy with `has_children:` and `parent:` settings

For more options see GitHub's [yaml front matter documentation](https://docs.github.com/en/contributing/writing-for-github-docs/using-yaml-frontmatter)


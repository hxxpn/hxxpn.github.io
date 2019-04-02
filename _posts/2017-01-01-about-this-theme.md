---
title: "About this theme"
---

## Installation (recommended)

Just fork the repo and adjust the `_config.yml` to use with [Github Pages](https://pages.github.com/) and your page is done.

*Note:* If you want to use this theme in a subfolder, then you need to create a `gh-pages` branch in your repo.

## Installation (jekyll-remote-theme method)

You can also create an empty repo, add `index.html` and `archive.html` files, which can be empty but need to contain front matter, and add this to your `_config.yml`:

```yaml
remote_theme: niklasbuschmann/contrast

plugins:
  - jekyll-remote-theme
```

## Features

 - supports dark mode in macOS Mojave
 - MathJax support
 - no external ressources
 - included archive page
 - supports pagination
 - feed generation
 - responsive
 - syntax highlighting
 - supports comments via [disqus](https://disqus.com/) or [isso](http://posativ.org/isso/)

## Based on

- [Minima](https://github.com/jekyll/minima)
- [Lagrange](https://github.com/LeNPaul/Lagrange)
- [Font Awesome](http://fontawesome.io/)
- [KaTeX](https://katex.org/)
- [Pygments](https://github.com/richleland/pygments-css)

## License

[public domain](http://unlicense.org/)

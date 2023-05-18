# ♻️ Resources for a Resource-Saving Internet
**An English translation of [korayer's RE;FERI](https://referi.de)**

---

## Description

A while ago, I stumbled upon korayer's RE;FERI, a site that both conveyed information about the environmental impact of the web, as well as resources to create visually pleasing sites without Javascript and other complex, resource-intensive technologies. Most notably, it provides a template for a CSS grid system that allows the user to create more complex layouts than vanilla HTML provides for.

To make this a better reference for myself, as well as for others that speak English rather than German, I opted to translate the site and it's resources (as well as the second section of this README). **Disclaimer, I am not a German speaker. This translation has been done partially with Google Translate, as well as simply reconstructing the original author's intent.**

The best way to learn more is to simply [check out the site](https://referi.ineedmore.coffee). Thank you for your interest in a free and resource-efficient web!

## Using these Resources

**In this folder you will find four files and one subfolder:**

1. `index.html`
2. `readme.md`
3. `images/`
4. `template/`

### `index.html`

This file powers the example site, with a variety of information on resource-efficient web design. Visit the live version [here](https://referi.ineedmore.coffee)!

### `readme.md`

You're reading this file right now.

### `images`

This folder contains various images used on the example site.

### `template`

This folder contains the files necessary to create your own website using the framework outlined here.

#### `template/index.html`

This is the document you need to modify to create your own website. A few paragraphs have already been provided for reference. Open the file in a browser to preview it. If you don't know how to write HTML yet, Mozilla has a great resource on how to get started [here](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics).

#### `template/grid.css` and `template/grid-12.css`

Both of these files contain the CSS grid system that allows for more complex layouts and arrangements of items. `grid.css` (what `index.html` is set to use by default) uses an 8-column grid, while `grid-12.css` is a version with a 12 column grid.

`<cell span=3>` creates a cell that is 3 columns long. If there is no space for it in the current line, it flows over to the next line. `<cell span=5-8>` creates a cell starting in the 5th column and ending in the 8th column.

#### `template/info.md`

This document contains information about using the template, largely a repeat of the section you're reading now.

---

## Tasks

- [x] Upload original German files
- [x] Translate texts to English
- [x] Add automatic [dark mode](https://bt.ht/html-dark-mode/)

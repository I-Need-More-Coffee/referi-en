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
2. `grid.css`
3. `grid-12.css`
4. `README.md`
5. `posters`

### `index.html`

This file powers the example site, with a variety of information on resource-efficient web design.

### `template.html`

This is the document you need to modify to create your own website. A few paragraphs have already been provided for reference. Open the file in a browser to preview it, or visit the live version [here](https://referi.ineedmore.coffee). If you don't know how to write HTML yet, Mozilla has a great resource on how to get started [here](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics).

### `grid.css` and `grid-12.css`

Both of these files contain the CSS grid system that allows for more complex layouts and arrangements of items. `grid.css` (what `index.html` is set to use by default) uses an 8-column grid, while `grid-12.css` is a version with a 12 column grid.

`<cell span=3>` creates a cell that is 3 columns long. If there is no space for it in the current line, it flows over to the next line. `<cell span=5-8>` creates a cell starting in the 5th column and ending in the 8th column.

### `README.md`

You're reading this file right now.

### `poster1.html and poster2.html`

The HTML files used to generate the posters linked to in `index.html`

### `pdfs`

This folder contains the PDF files that are linked to in `index.html` as examples of how to use this grid system for designing posters.

### `images`

This folder contains various images used on the site.

---

## Tasks

- [x] Upload original German files
- [x] Translate texts to English
- [ ] Create a variant with automatic [dark mode](https://bt.ht/html-dark-mode/)

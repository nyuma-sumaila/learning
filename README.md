# HTML Practice Website

A collection of static HTML pages used to practice web development, media embeds,
shopping layouts, and basic JavaScript.

## Pages

| Page | Description |
| --- | --- |
| [`index.html`](index.html) | Operating system installation guide with Windows setup topics, an image, links, and email. |
| [`lyrics.html`](lyrics.html) | A song and media practice page with audio, lists, a definition list, and a store-hours table. |
| [`Tech.html`](Tech.html) | A small laptop and phone accessories storefront layout. |
| [`webtech.html`](webtech.html) | A responsive BoTech shopping page with products, categories, search, filtering, cart counts, and a flash-sale countdown. |

## Included Assets

- `Omah-Lay-Safe-Haven.mp3` - audio used by `lyrics.html`
- `Spero 1.png` - project image asset
- `a dog.png` - image used by `index.html`

## Features

- Semantic HTML elements and common page layouts
- Embedded audio and video markup
- Internal and external links
- CSS-based responsive product cards and navigation
- JavaScript product search and category filtering
- Shopping cart count updates
- A live flash-sale countdown

## Running the Project

No build tools or dependencies are required.

1. Clone or download this repository.
2. Open `index.html` in a web browser.
3. Use the page links and HTML files to explore the examples.

For a local server on Windows, open a terminal in the project folder and run:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Notes

- `Tech.html` references `images/hero.jpg` and `js/main.js`, which are not currently included in this repository.
- `lyrics.html` references `Omah-Lay-Safe-Haven.mp4`, but the MP4 file is not currently included.
- Product images in `webtech.html` are loaded from Unsplash and require an internet connection.
# Emmanuel Lucky — Portfolio

A small personal portfolio site built as my resume project. It introduces me, shows what I've been building, lists my current skills, and gives a way to get in touch.

## What it's built with

- **HTML5** — semantic markup, no template or generator
- **CSS3** — a single hand-written stylesheet (`styles.css`) using Flexbox, Grid, and custom properties, with a responsive layout that adapts down to phone screens
- **SVG** — a self-drawn monogram used as the hero image
- No frameworks, no build step. Open `index.html` in a browser and it runs.

## Structure

```
index.html      – site content and structure
styles.css      – all styling, colours, type, and layout
assets/
  avatar.svg    – hero illustration
```

## Running it locally

Clone the repo and open `index.html` in any browser — no build tools or server required.

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
open index.html
```

## Notes

The hardest part was keeping the CSS specificity clean between the section-level and element-level selectors so paddings and colors didn't fight each other as sections were added — worth double-checking if you extend this.

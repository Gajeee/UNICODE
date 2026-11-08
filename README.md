# Ghub Codes

A free ASCII and HTML entity toolkit. One HTML file, no build step, no dependencies.

**Live:** https://gajeee.github.io/ghub-codes/

## What it does

| Tab | Features |
|---|---|
| **Lookup** | About 1,500 characters across ASCII, Latin, Greek, Cyrillic, arrows, math, boxes and symbols. Search by character, decimal, hex, `U+00A9`, `&rarr;` or name. One click copies the character, decimal/hex/named entity, CSS escape or JS escape. |
| **Converter** | Text to named, decimal and hex entities, plus UTF-8 bytes in decimal, hex and binary. Decode entities back to text. |
| **Cheat sheet** | The five characters you must escape, 39 copy-ready favourites, and quick tips. |
| **Copy-paste designs** | Fancy fonts, decorated text, text boxes, dividers, bullets and kaomoji. |
| **ASCII art** | Big block-letter banners with 3D shadow, image to ASCII converter (runs in your browser), and a small art gallery. |

## Publish in 4 steps (GitHub Pages)

1. Create a new repo named `ghub-codes` on GitHub (public).
2. Put `index.html` and `README.md` in the repo folder, then:

   ```bash
   git init
   git add .
   git commit -m "Ghub Codes"
   git branch -M main
   git remote add origin https://github.com/Gajeee/ghub-codes.git
   git push -u origin main
   ```

3. On GitHub: **Settings > Pages > Source: Deploy from a branch > `main` / `(root)` > Save**.
4. Wait about a minute. Your site is live at `https://gajeee.github.io/ghub-codes/`.

## Share on Discord

Paste the link in any channel. Discord reads the Open Graph tags in `index.html` and shows a lime-coloured embed with the title and description.

To get a preview image in the embed:

1. Take a screenshot of the site (about 1200 x 630 works best).
2. Save it as `preview.png` next to `index.html`.
3. Commit and push it.

Discord caches embeds. If you change the preview later, add `?v=2` to the link to force a refresh.

## Customising

- **Colours:** edit the CSS variables at the top of the `<style>` block (`--ac` is the lime accent).
- **Links in the head:** if your username or repo name differs, update the `og:url` and `og:image` URLs in `index.html`.
- **Footer credit:** search for `Made By Gajee Hub`.

## Notes

- Works offline once loaded, apart from the Google Fonts (it falls back to system fonts).
- Character data covers ASCII 0-127 and common Unicode blocks. Codes 128-159 are left out on purpose, since they are invisible control codes.

---

Made By [Gajee Hub](https://gajeee.github.io/Portfolio/)

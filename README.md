# Original Brave Shots

Portfolio site for Precieux Tchibozo (Original Brave Shots) - portrait, fashion,
event and product photography.

Static single-page site. No build step, no dependencies.

## Run locally

    python3 -m http.server 8000

Then open http://localhost:8000

## Structure

    index.html            everything - markup, styles, script
    assets/logo.png       OB Shots mark, recoloured to bone, transparent
    assets/favicon.png
    assets/photos/*.webp  24 portfolio images, 1000px wide

Photo metadata (id, category, title, tag) lives in the `PHOTOS` array near the
bottom of index.html. Categories: fashion, beauty, editorial, events, product, print.

## Deploy

GitHub Pages, deploy from branch `main`, folder `/ (root)`.

## Open items

- FR/EN toggle renders but does not switch yet
- Frame titles are placeholders pending real credits
- Four campaigns (Dolait, Le Jus de Tam Tam, Sistywax, Gari Kivo) marked
  "Coming soon" until imagery arrives
- WhatsApp number and city not yet added to the contact section

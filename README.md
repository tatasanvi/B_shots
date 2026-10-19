# Original Brave Shots

Portfolio site for Precieux Tchibozo (Original Brave Shots) - portrait, fashion,
event and product photography.

Static single-page site. No build step, no dependencies.

## Run locally

    python3 -m http.server 8000

Then open http://localhost:8000

## Structure

    index.html            everything - markup, styles, script
    admin.html            Studio Manager - client and photo management interface
    assets/logo.png       OB Shots mark, recoloured to bone, transparent
    assets/favicon.png
    assets/photos/*.webp  24 portfolio images, 1000px wide

Photo metadata (id, category, title, tag) lives in the `PHOTOS` array near the
bottom of index.html. Categories: fashion, beauty, editorial, events, product, print.

## Deploy

GitHub Pages, deploy from branch `main`, folder `/ (root)`.
Live site: https://tatasanvi.github.io/B_shots/
Studio Manager: https://tatasanvi.github.io/B_shots/admin.html

## Studio Manager (admin.html)

L'interface d'administration permet a Precieux de :
1. **Ajouter de nouvelles photos** : glissez-deposez l'image, definissez la categorie et le titre, puis publiez directement sur GitHub.
2. **Gerer les clients et campagnes** : ajoutez de nouveaux clients (marques, prestations, annees), basculez leur statut ("En ligne" ou "Bientot"), et publiez en 1 clic vers le site.
3. **Consulter la galerie** : visualisez toutes les photos actuellement actives dans le portfolio.

### Configuration du token GitHub (a faire une seule fois)
1. Rendez-vous sur https://github.com/settings/tokens/new
2. Donnez une note (ex: `Studio Manager`) et cochez le scope **`repo`**.
3. Cliquez sur **Generate token** et copiez la cle.
4. Dans le Studio Manager (onglet **Parametres**), collez le token et cliquez sur **Enregistrer**.
5. Le token est sauvegarde localement et securise dans votre navigateur.

## Completed

- Full bilingual FR/EN toggle with instant language switching and localStorage persistence
- Direct WhatsApp link (+229 52 94 56 44) and location (Cotonou, Benin) in the contact section
- High-end Obsidian Black, Pure White and Champagne Gold color palette
- Studio Manager (admin.html) for effortless photo, client and campaign management directly from GitHub Pages
- Zero-backend architecture powered by GitHub API and GitHub Pages

## Open items

- Frame titles are placeholders pending real credits
- Four campaigns (Dolait, Le Jus de Tam Tam, Sistywax, Gari Kivo) marked
  "Coming soon" until imagery arrives


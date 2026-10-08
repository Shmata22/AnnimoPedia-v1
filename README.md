# Aniimopédia — V1

Application statique mobile-first inspirée de la présentation visuelle d'Aniimo : cartes verticales, fond clair bleuté, panneaux translucides, progression, filtres et fiche détaillée.

## Structure
- `index.html` — interface
- `styles.css` — design responsive
- `app.js` — logique de collection, favoris, recherche, import/export
- `aniimo.json` — données séparées
- `./001.svg` … — emplacements d'images remplaçables

## Ajouter les vraies images
Remplacez les SVG de `./` par vos fichiers, puis modifiez le champ `image` dans `aniimo.json` si l'extension change (ex. `./001.webp`). Les images peuvent aussi être importées directement depuis la fiche d'un Aniimo : elles sont alors conservées dans le navigateur.

## Déploiement GitHub Pages
Publier le contenu de ce dossier à la racine du dépôt Pages. Aucun framework ni serveur n'est nécessaire.

## Données initiales
L'index initial suit les 82 entrées numérotées publiées sur le Wiki officiel au 7 octobre 2026. Les captures sont initialisées à 1–81 pour correspondre à une collection déjà avancée ; vous pouvez tout remettre à zéro depuis les données ou le navigateur.

Les champs non confirmés sont laissés vides et l'interface affiche `???` plutôt que d'inventer des informations.

# Rapido Website

Site vitrine statique de [Rapido](https://github.com/shimon3/rapido), un accélérateur de téléchargement open source pour Windows.

## Aperçu local

Ouvrez `index.html` dans un navigateur. Aucun build ni gestionnaire de dépendances nécessaire.

## Publication sur GitHub Pages

1. Créez un dépôt public `shimon3/rapido-website`.
2. Envoyez `index.html`, `README.md` et `.nojekyll` à la racine de la branche `main`.
3. Dans **Settings → Pages**, choisissez **Deploy from a branch**, **main**, **/(root)**, puis enregistrez.
4. La page sera accessible à `https://shimon3.github.io/rapido-website/` une fois la publication terminée.

## Liens de téléchargement

Les boutons du site renvoient directement à la release Rapido 1.2.0 du dépôt de l'application. Mettre à jour les liens lorsque la version change.

## Séparation des projets

Ce dépôt contient uniquement le site Web de présentation. Le code de l'application reste dans `shimon3/rapido`.

## Languages

The site includes French, English and Hebrew translations. The FR/EN/HE selector stays in the same position at the right of the navigation. Hebrew page content uses RTL, while navigation remains LTR. The selection is stored locally in the browser. No translation service or API key is needed.

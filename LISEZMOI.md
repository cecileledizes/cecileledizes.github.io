# Mettre le site en ligne avec GitHub Pages

## 1. Créer le dépôt
1. Sur GitHub, clique sur **New repository**.
2. Nomme-le exactement **`cecileledizes.github.io`**, mets-le en **Public**, puis crée-le.

## 2. Ajouter les fichiers
Le plus simple est de passer par le navigateur : dans le dépôt, clique sur **Add file → Upload files**, puis glisse-dépose le contenu du zip (`index.html`, `.nojekyll`, le dossier `assets/`). Termine avec **Commit changes**.

Le site sera en ligne d'ici une à deux minutes à l'adresse **https://cecileledizes.github.io**. Si ce n'est pas le cas, va dans **Settings → Pages**, choisis **Deploy from a branch**, puis la branche `main` et le dossier `/ (root)`.

## 3. Compléter les « TODO »
Dans `index.html`, cherche `TODO` avec Ctrl+F. Tu dois compléter :
- ton e-mail (il apparaît à deux endroits) ;
- l'URL de ton profil Google Scholar et celle de ton ORCID ;
- une phrase sur ta situation actuelle, dans les sections *About* et *CV* ;
- le lien vers ta thèse (HAL ou theses.fr), dans la section *Publications* ;
- le lien vers les slides du GdR MFGA (le lien actuel du dépôt *communications* pointe vers les slides des Houches).

Tu peux modifier le fichier directement sur GitHub en cliquant sur l'icône crayon.

## 4. Ajouter les fichiers du dossier `assets/`
- `assets/photo.jpg` : ta photo, au format carré. Tant qu'elle n'est pas là, un cercle vide s'affiche à la place.
- `assets/CV_LeDizes.pdf` : ton CV.
- `assets/wavefield.png` (facultatif) : une figure produite avec ITIDES-3D. Pour l'afficher, retire le commentaire `<!-- ... -->` autour du bloc `<figure>` dans la section *Research*.

## 5. Relier le site à ton profil
- Dans la bio de ton profil GitHub, renseigne le champ **Website** avec `https://cecileledizes.github.io`.
- Ajoute ce lien en haut du README de ton profil.
- Mets-le aussi dans ta signature d'e-mail et dans tes candidatures.

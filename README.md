# 👕 Gestion des vêtements homme

Site statique prêt pour GitHub Pages, avec formulaire pour ajouter, modifier et supprimer des vêtements, et importer une photo JPG/PNG/WebP.

## Publication

1. Créez un dépôt GitHub.
2. Placez `index.html` et `data.js` à la racine du dépôt.
3. Dans **Settings → Pages**, choisissez **Deploy from a branch**, `main`, `/ (root)`.

## Utilisation

Le formulaire accepte titre, marque, quantité, prix en DA, taille, lien Facebook et photo. Les images sont redimensionnées et compressées dans le navigateur.

**Limite importante :** GitHub Pages est statique. Les modifications sont sauvegardées en `localStorage`, uniquement sur le navigateur utilisé. Elles ne sont pas publiées sur GitHub ni visibles par les autres visiteurs. Effacer les données du navigateur peut effacer les modifications. Pour une gestion centralisée et partagée, utilisez un backend avec authentification, base de données et stockage d'images.

Les exemples initiaux se trouvent dans `data.js`.

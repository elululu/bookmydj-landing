# BOOKMYDJ Landing

Mini site statique public pour presenter BOOKMYDJ, fournir une URL au portail SoundCloud Developer et preparer les pages utiles pour App Store / Google Play.

## Pages

- `index.html` : presentation rapide du produit
- `privacy.html` : politique de confidentialite
- `support.html` : support et suppression de compte

## Publication GitHub Pages

1. Creer un nouveau repository public, par exemple `bookmydj-landing`.
2. Copier ces fichiers a la racine du repository.
3. Activer GitHub Pages dans `Settings > Pages` avec `Deploy from a branch`, branche `main`, dossier `/root`.
4. Utiliser l'URL publique GitHub Pages comme website SoundCloud et comme URL support/confidentialite App Store.

## URL SoundCloud

Dans SoundCloud Developer, utiliser l'URL publique de la landing dans le champ Website.

Pour OAuth mobile, ajouter aussi le redirect URI de l'app :

```text
bookmydj://soundcloud-callback
```

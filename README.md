# Maktabet Naje7 — Site vitrine

Site statique HTML/CSS/JS pour **Maktabet Naje7 / مكتبة النجاح**.

## Mise à jour incluse

- Design plus local et plus commercial.
- Beaucoup plus d'images/visuels.
- Galerie 12 images.
- Produits avec images.
- Bouton WhatsApp direct: `97981347`.
- Compatible Vercel sans build.

## Remplacer les images par des photos réelles

Les images temporaires sont dans:

```txt
assets/images/
```

Pour un rendu plus réel, remplace ces fichiers par des photos de la boutique avec les mêmes noms, par exemple:

- `boutique-books.svg`
- `printing-service.svg`
- `electronic-accessories.svg`
- `gallery-01.svg` jusqu'à `gallery-12.svg`

Tu peux aussi utiliser `.jpg` ou `.png`, mais dans ce cas il faut modifier les liens dans `index.html`.

## Mettre à jour GitHub

Après modification:

```bash
git add .
git commit -m "Update design with gallery"
git push
```

Vercel fera la mise à jour automatiquement.

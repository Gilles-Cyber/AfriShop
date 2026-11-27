# AfriShop

Site vitrine d'AfriShop, une boutique de produits africains : mode, artisanat et produits locaux.

Ce projet a été réalisé dans le cadre du TP « Git & GitHub — Initiation au versionnage ».
Chaque fonctionnalité a été développée, testée, enregistrée dans un commit séparé, puis publiée sur GitHub.

## Contenu du site

- **Menu de navigation** : liens Accueil, Produits, Contact (ancres `#accueil`, `#produits`, `#contact`)
- **Accueil** : titre, description et bouton vers le catalogue
- **Catalogue** : trois cartes produits (image, titre, description, prix)
  - Chemise africaine — 15 000 FCFA
  - Panier artisanal — 8 000 FCFA
  - Café local — 5 000 FCFA
- **Contact** : adresse fictive, horaires, e-mail
- **Pied de page**
- Affichage adapté aux petits écrans (cartes qui passent à la ligne, menu sur deux lignes)

## Auteur

Kemzeu Gilles — [Gilles-Cyber](https://github.com/Gilles-Cyber)

## Technologies

- HTML5
- CSS3 (Flexbox, media queries)
- Git et GitHub pour le versionnage

## Structure du projet

```
AfriShop/
├── index.html
├── style.css
├── images/
│   ├── chemise.svg
│   ├── panier.svg
│   └── cafe.svg
└── README.md
```

## Lancer le site

1. Cloner le dépôt :
   ```
   git clone https://github.com/Gilles-Cyber/AfriShop.git
   cd AfriShop
   ```
2. Ouvrir le fichier `index.html` dans un navigateur (double-clic).

Aucune installation n'est nécessaire : le site est entièrement statique.

## Versions

| Tag    | Contenu                                  |
|--------|------------------------------------------|
| v1.0.0 | Structure, menu de navigation, accueil   |
| v1.1.0 | Catalogue de produits et contact         |
| v1.1.1 | Correction de l'affichage du catalogue   |

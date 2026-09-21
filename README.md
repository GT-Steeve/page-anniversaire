# Fichiers d'Anniversaire

Une petite collection de pages d'anniversaire, une par ami (ou par groupe d'amis nés le même jour). Chaque page est un fichier HTML autonome, sans build ni dépendance, pensé pour être ouvert directement dans un navigateur ou servi tel quel (GitHub Pages, hébergement statique, etc.).

## Structure

```
.
├── index.html              # Hub : écran de sélection listant chaque page
├── djo/
│   └── index.html          # Anniversaire de Djonathan (Victeam) — DA arcade/fighting-game
└── mickaelDyones/
    └── index.html          # Anniversaire commun de Mickael (Sakura) et Dyones (Sasuke) — DA manga Naruto
```

- **`index.html`** : page d'accueil du dépôt, sert de sommaire et renvoie vers chaque page d'anniversaire.
- **`djo/index.html`** : thème arcade néon (écran VS, historique de combos, sélection de stage, easter eggs).
- **`mickaelDyones/index.html`** : thème manga façon Naruto (Team 7, feuille de mission, chemins après l'ellipse).

## Ajouter un nouvel ami

1. Créer un nouveau dossier à la racine, nommé d'après la personne (ex. `prenom/`).
2. Y placer un `index.html` autonome (voir les deux pages existantes comme modèles).
3. Ajouter une carte de lien vers cette page dans `index.html` (le hub), dans `.grid`.

## Utilisation

Aucune installation nécessaire : ouvrir `index.html` dans un navigateur, ou déployer le dossier tel quel sur un hébergement statique (GitHub Pages, Netlify, Vercel, etc.).

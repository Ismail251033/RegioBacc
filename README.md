# RegioBacc – Plateforme de révision Français 1BAC

## Présentation
RegioBacc est une plateforme éducative complète pour préparer le régional de français de 1BAC au Maroc.
Développée en HTML/CSS/JavaScript vanilla, sans aucune dépendance externe.

## Fonctionnalités
- 3 romans complets : La Boîte à merveilles, Antigone, Le Dernier Jour d'un Condamné
- Résumés généraux et chapitres détaillés
- Fiches personnages, thèmes, citations
- Flashcards interactives avec animation flip
- QCM 3 niveaux (Facile / Moyen / Difficile) avec corrections pédagogiques
- Tableau de bord avec statistiques et badges
- Chatbot pédagogique hors ligne
- Dark mode / Light mode
- PWA installable sur mobile
- 100% offline via LocalStorage

## Installation
1. Décompressez le dossier
2. Ouvrez `index.html` dans un navigateur moderne
3. Sur mobile : utilisez le bouton "Installer" pour l'ajouter à l'écran d'accueil

## Structure
```
regiobacc/
├── index.html        ← Application complète (HTML + CSS + JS)
├── manifest.json     ← Manifest PWA
├── sw.js             ← Service Worker (offline)
└── README.md
```

## Technologies
- HTML5, CSS3 (variables, glassmorphism, animations)
- JavaScript ES6+ vanilla
- LocalStorage pour la persistance
- Service Worker pour le mode hors ligne

## Contenu pédagogique
Conforme au programme officiel marocain de 1BAC.

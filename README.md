# Portfolio Nina Carducci - Optimisation SEO et Performances

![Static Badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Static Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Static Badge](https://img.shields.io/badge/CSS-3399FF?style=for-the-badge&logo=css3&logoColor=white)
![Static Badge](https://img.shields.io/badge/Lighthouse-F44B21?style=for-the-badge&logo=lighthouse&logoColor=white)

Ce projet consiste à optimiser un site de photographe existant, "Nina Carducci", afin d'améliorer ses performances, son référencement (SEO), et son accessibilité. L'objectif était de partir d'un code non optimisé pour arriver à un site rapide, bien classé sur les moteurs de recherche et utilisable par tous.

## Démo en ligne

[Voir le site →](https://guillaumebourlier.github.io/Nina-Carducci/)

## Audit Lighthouse

Un audit Lighthouse a été réalisé avant et après les optimisations pour mesurer l'impact des changements.


## Optimisations et Réalisations

### 1. Optimisation des performances

*   **Images :**
    *   Compression des images pour réduire leur poids.
    *   Conversion au format nouvelle génération `WebP`.
    *   Implémentation du chargement différé (`loading="lazy"`) pour les images hors du viewport.
    *   Mise en place d'images responsives avec l'attribut `srcset` et la balise `<picture>` pour servir des tailles d'images adaptées à chaque appareil.
    *   Préchargement des images critiques du carrousel avec `<link rel="preload">`.
*   **Code :**
    *   Minification des fichiers CSS et JavaScript pour réduire leur taille.
    *   Utilisation de versions minifiées des bibliothèques externes (Bootstrap, jQuery).

### 2. Optimisation du SEO

*   **Sémantique HTML :**
    *   Utilisation de balises sémantiques (`<header>`, `<main>`, `<footer>`, `<section>`, `<nav>`, `<article>`) pour structurer le contenu.
    *   Hiérarchie des titres (`<h1>`, `<h2>`, `<h3>`) corrigée pour une meilleure compréhension par les moteurs de recherche.
*   **Métadonnées :**
    *   Ajout de méta-balises pertinentes (`description`, `author`, `keywords`).
    *   Configuration des balises Open Graph et Twitter Cards pour un meilleur partage sur les réseaux sociaux.
*   **Référencement Local :**
    *   Intégration de données structurées (Schema.org au format `JSON-LD`) pour le référencement local, incluant les informations de l'entreprise (adresse, horaires, etc.).

### 3. Amélioration de l'accessibilité

*   **Navigation et Contenu :**
    *   Ajout d'attributs `alt` descriptifs pour toutes les images.
    *   Utilisation d'attributs ARIA (`aria-label`, `aria-current`) pour améliorer la navigation pour les lecteurs d'écran.
*   **Formulaires :**
    *   Association des `label` à leurs `input` respectifs pour une meilleure accessibilité des formulaires.

## Technologies utilisées

*   HTML5
*   CSS3
*   JavaScript
*   Bootstrap
*   jQuery
*   Lighthouse (pour l'audit)

## Pour commencer

Pour visualiser le projet, vous pouvez soit visiter la démo en ligne, soit cloner le dépôt et ouvrir le fichier `index.html` dans votre navigateur.

```bash

git clone https://github.com/GuillaumeBourlier/Nina-Carducci.git


cd Nina-Carducci
```

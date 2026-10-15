Test it now: https://desdes-gfmhom6pl-bibos-projects-aa1e5cef.vercel.app/

# Dice Forge 🎲

> A stylish, browser-based dice roller for forging your destiny.

## Description

Dice Forge is a lightweight dice-rolling application built as a single self-contained HTML page. It offers a dark, fantasy-inspired interface with gold accents, animated interactions, and support for several common tabletop dice.

The application is entirely client-side: no backend, build step, or installation is required. Open `index.html` in a modern web browser to start rolling.

## Features

- Choose between **D4, D6, D8, D10, D12, D20, and percentile D%** dice.
- Roll between **1 and 20 dice** at a time.
- Use quick presets for 1, 2, 3, 4, 5, 6, or 10 dice.
- Keep individual dice between rolls with the **hold** feature.
- Hold or release all dice with one click.
- Re-roll only the dice that are not held.
- Display the total of every roll.
- View statistics for the latest roll:
  - minimum value;
  - maximum value;
  - average;
  - sum.
- Review the last **10 rolls** in the history panel and clear the history when needed.
- Use the **Space** or **Enter** key to roll when the page body is focused.
- Enjoy responsive layouts and animated dice reveals, roll effects, particles, and held-dice feedback on mobile and desktop screens.

## How to use

1. Open `index.html` in your browser.
2. Select a die type. The D6 is selected by default.
3. Choose the number of dice using `+`, `−`, or a quick preset.
4. Click **Lancer les dés** to roll.
5. Click an individual result to hold it for the next roll.
6. Roll again to keep held dice and re-roll the others.
7. Use **Tout garder** or **Tout relâcher** to manage all dice at once.

Changing the die type releases any held dice. The number of dice is constrained to a minimum of 1 and a maximum of 20.

## Technology

- HTML5
- CSS3, including custom properties, gradients, responsive media queries, and animations
- Vanilla JavaScript
- Google Fonts: Cinzel Decorative and Crimson Pro

The project has no external JavaScript dependencies and contains all application logic in `index.html`.

## Project structure

```text
.
├── index.html   # Complete application: markup, styles, and JavaScript
└── README.md    # Project documentation
```

## Notes

- Results are generated in the browser with JavaScript's `Math.random()` function.
- Roll history is stored only in the current page session and is not persisted after reloading the page.
- The interface text is currently primarily in French.

---

# Dice Forge 🎲 — Version française

> Un lanceur de dés élégant dans le navigateur pour forger votre destin.

## Description

Dice Forge est une application légère de lancer de dés, conçue comme une page HTML autonome. Elle propose une interface sombre inspirée de la fantasy, avec des accents dorés, des animations et la prise en charge de plusieurs dés classiques des jeux de rôle et de plateau.

L'application fonctionne entièrement côté client : aucun serveur, aucune installation et aucune étape de compilation ne sont nécessaires. Il suffit d'ouvrir `index.html` dans un navigateur moderne pour commencer à lancer les dés.

## Fonctionnalités

- Choix entre les dés **D4, D6, D8, D10, D12, D20 et D%**.
- Lancer de **1 à 20 dés** simultanément.
- Préréglages rapides pour 1, 2, 3, 4, 5, 6 ou 10 dés.
- Possibilité de **garder** certains dés entre deux lancers.
- Actions pour garder ou relâcher tous les dés en un clic.
- Relance uniquement des dés qui ne sont pas gardés.
- Affichage du total de chaque lancer.
- Statistiques du dernier lancer :
  - valeur minimale ;
  - valeur maximale ;
  - moyenne ;
  - somme.
- Historique des **10 derniers lancers**, avec possibilité de l'effacer.
- Utilisation de la touche **Espace** ou **Entrée** pour lancer les dés lorsque le corps de la page est sélectionné.
- Interface responsive pour ordinateur et mobile, avec animations de révélation, effets de lancer, particules et indication visuelle des dés gardés.

## Utilisation

1. Ouvrez `index.html` dans votre navigateur.
2. Sélectionnez un type de dé. Le D6 est sélectionné par défaut.
3. Choisissez le nombre de dés avec `+`, `−` ou un préréglage rapide.
4. Cliquez sur **Lancer les dés**.
5. Cliquez sur un résultat pour garder le dé au prochain lancer.
6. Relancez les dés : les dés gardés restent identiques et les autres sont relancés.
7. Utilisez **Tout garder** ou **Tout relâcher** pour gérer tous les dés en même temps.

Changer de type de dé relâche les dés gardés. Le nombre de dés est limité à un minimum de 1 et un maximum de 20.

## Technologies

- HTML5
- CSS3, avec variables personnalisées, dégradés, media queries responsives et animations
- JavaScript natif, sans framework
- Google Fonts : Cinzel Decorative et Crimson Pro

Le projet ne possède aucune dépendance JavaScript externe : toute la logique de l'application se trouve dans `index.html`.

## Structure du projet

```text
.
├── index.html   # Application complète : HTML, CSS et JavaScript
└── README.md    # Documentation du projet
```

## Remarques

- Les résultats sont générés dans le navigateur grâce à la fonction JavaScript `Math.random()`.
- L'historique est conservé uniquement pendant la session de la page et n'est pas sauvegardé après un rechargement.
- L'interface est actuellement principalement en français.

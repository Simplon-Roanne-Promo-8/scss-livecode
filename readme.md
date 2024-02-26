# LiveCode SCSS

Ce LiveCode a pour but de mettre en pratique les principes fondamentaux du préprocesseur SCSS (Sassy CSS), un outil puissant pour écrire du CSS de manière plus efficace et organisée.

# Principe de SCSS

SCSS est une syntaxe de SASS, qui permet d'utiliser toutes les fonctionnalités de CSS ainsi que d'autres fonctionnalités qui n'existent pas dans CSS pur, telles que les variables, les boucles, les conditions, les fonctions, et plus encore. SCSS maintient la compatibilité avec la syntaxe de CSS, ce qui facilite l'apprentissage pour ceux qui sont déjà familiers avec le CSS.

# Contenu du LiveCode

- Les Variables : Permettent de stocker des valeurs réutilisables, telles que des couleurs, des polices, ou des dimensions.
- Les Mixins : Fonctions réutilisables qui acceptent des arguments, pour générer des blocs de CSS. Utilisé pour des effets de hover et pour flex-center dans cet exemple.
- Les Fonctions : Définitions réutilisables pour manipuler des valeurs, notamment pour créer des mix de couleurs aléatoires ou pour extraire des valeurs spécifiques d'un tableau.
- L’Imbrication : Permet d’écrire des sélecteurs à l’intérieur d’autres sélecteurs, qui reflète la structure HTML de manière plus naturelle.

# Installation

Pour compiler le fichier SCSS en CSS, vous aurez besoin d'un préprocesseur SCSS

`sass source/styles.scss destination/styles.css`

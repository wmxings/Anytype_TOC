[中文](../README.md) | [English](README_en-US.md) | [繁體中文](README_zh-TW.md) | [Русский](README_ru-RU.md) | [日本語](README_ja-JP.md) | [한국어](README_ko-KR.md) | [Deutsch](README_de-DE.md) | [Français](README_fr-FR.md)

# Anytype Table des matières flottante

## Contexte du projet
Depuis 2022, les utilisateurs de la communauté Anytype demandent l'ajout d'une fonction de table des matières flottante. Malheureusement, en avril 2025, cette fonctionnalité n'est toujours pas incluse dans le plan de développement officiel. Curieusement, Notion, l'un des principaux concurrents d'Anytype, ne montre pas non plus beaucoup d'enthousiasme pour l'implémentation de cette fonction.

## Solution
Ce projet implémente une table des matières flottante simple et élégante pour Anytype en utilisant du CSS personnalisé. Cette solution correspond à l'approche partagée par l'utilisateur de la communauté [@sandroid](https://community.anytype.io/t/custom-table-of-contents-custom-css/27360/8).

Dans le processus de conception, nous nous sommes inspirés du style de la table des matières flottante de sspai.com. Malgré la limitation d'Anytype qui ne prend en charge que le CSS personnalisé sans JS, le résultat final est néanmoins impressionnant.

## Démonstration
![Démonstration de la table des matières flottante](../image/IMG_20250411_234639.gif)

## Fonctionnalités
- Mise en page simple et élégante de la table des matières flottante
- La table des matières suit le défilement de la page pour une navigation facile
- Effets de survol pour les éléments de la table des matières

## Utilisation
1. Ouvrez Anytype et accédez à `Fichier -> Ouvrir -> CSS personnalisé`
2. Copiez le contenu de `custom.css` ou `custom.min.css` dans le fichier `CSS personnalisé`
3. Redémarrez Anytype pour appliquer les modifications

## Notes
- Pour personnaliser le style, vous pouvez modifier les paramètres dans `custom.css` 
# Projet ProFound

#### Estimer si un projet est financé, et si oui pour quel montant !

## Contexte

Nous sommes un groupe d'étudiants inégnieurs au CNAM de Niort qui avons réalisé un travail de classification sur le financement de projets.

## Objectifs

A partir du jeu de données dont nous avons à notre disposition, l'objectif va être de déterminer si oui ou non un projet sera financé et si oui, à quel montant ?

## Présentation du data set

Voici la présentation des différentes variables issues de notre dataset :




| Variable | Type     | Description                |  Exemple    | Valeurs uniques |
| :-------- | :------- | :------------------------- | :----------- | :------- |
| `ID` | `int` | Identifiant unique du projet |  | 378657   | 
| `Nom` | `string` | Nom du projet |   | 375764   | 
| `Categorie` | `string` | Catégorie du projet |   | 159   | 
| `categorie_principale` | `string` | Catégorie de la campagne |   | 15   | 
| `monnaie` | `string` | Catégorie de la campagne |   | 14   | 
| `date_butoire` | `date` | Monnaie utilisée |   | 3164   | 
| `objectif` | `float` | Date butoire pour le financement |   | 8353   | 
| `lancement` | `string` | Objectif de financement du projet |   | 378085   | 
| `promesse` | `float` | Date de lancement |   |  62130  | 
| **`etat`** | **`string`** | Etat du projet (financé, en cours, ...) |   |  6  | 
| `supporters` | `int` | Nombre de financeurs potentiels |   |  3963  | 
| `pays` | `string` | Pays des promesses |   |  23  | 
| `promesse_usd1` | `float` | Montant promis converti en dollars US par la plateforme |   | 95454   | 
| `promesse_usd2` | `float` | Montant promis converti en dollars US par fixer.io |   |  106065  | 
| `objectif_usd` | `float` | Objectif de financement converti en dollars US par fixer.io |   |  50339  | 

## Equipe du projet

- Théo KOESSLER
- Pierre VAN DEN BOOM
- Enzo RIGAULT
- Gwendal ROLLAND
- Maxime GARNIER
- Florian GABORIEAU

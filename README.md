# Projet ProFound

#### Projet Python de 2ème année du CNAM Niort

## Contexte

Nous sommes un groupe d'étudiants inégnieurs au CNAM de Niort qui avons réalisé un travail de classification sur le financement de projets.

## Objectifs

A partir du jeu de données dont nous avons à notre disposition, l'objectif va être de déterminer si oui ou non un projet sera financé et si oui, à quel montant ?

## Présentation du data set

Voici la présentation des différentes variables issues de notre dataset :

| Variable                | Type          | Description                                                 |  Exemple              | Valeurs uniques |
| :---------------------- | :------------ | :---------------------------------------------------------  | :----------           | :------- |
| `ID`                    | `int`         | Identifiant unique du projet                                | 1000002330            | 378657   | 
| `Nom`                   | `string`      | Nom du projet                                               | Monarch Espresso Bar  | 375764   | 
| `Categorie`             | `string`      | Catégorie du projet                                         | Restaurants           | 159      | 
| `categorie_principale`  | `string`      | Catégorie de la campagne                                    | Food                  | 15       | 
| `monnaie`               | `string`      | Monnaie utilisée                                            | USD                   | 14       | 
| `date_butoire`          | `date`        | Date butoire pour le financement                            | 09/10/2015            | 3164     | 
| `objectif`              | `float`       | Objectif de financement du projet                           | 19500.0               | 8353     | 
| `lancement`             | `string`      | Date de lancement                                           | 11/08/2015  12:12:28  | 378085   | 
| `promesse`              | `float`       | Promesse de financement                                     | 0.0                   | 62130     
| **`etat`**              | **`string`**  | Etat du projet (financé, en cours, ...)                     | failed                | 6         
| `supporters`            | `int`         | Nombre de financeurs potentiels                             | 15                    | 3963      
| `pays`                  | `string`      | Pays des promesses                                          | GB                    | 23        
| `promesse_usd1`         | `float`       | Montant promis converti en dollars US par la plateforme     | 1283.0                | 95454    | 
| `promesse_usd2`         | `float`       | Montant promis converti en dollars US par fixer.io          | 2421.0                | 106065    
| `objectif_usd`          | `float`       | Objectif de financement converti en dollars US par fixer.io | 45000.0               | 50339    

## Equipe du projet

- Théo KOESSLER
- Pierre VAN DEN BOOM
- Enzo RIGAULT
- Gwendal ROLLAND
- Maxime GARNIER
- Florian GABORIEAU

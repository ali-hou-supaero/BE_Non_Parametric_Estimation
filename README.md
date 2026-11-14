# Régression non paramétrique et choix de bande passante

Bureau d’études ISAE-SUPAERO réalisé avec R et Quarto. Le document étudie la régression à noyau, l’estimateur de Nadaraya-Watson, l’effet de la bande passante et la validation croisée leave-one-out.

## Livrables

- [BE.qmd](BE.qmd) : source Quarto contenant calculs, réponses et graphiques.
- [BE.html](BE.html) : document HTML déjà rendu, à télécharger et ouvrir dans un navigateur.
- `BE_Non_Parametric_Estimation.Rproj` : projet RStudio.

## Reproduction

Le document utilise R, Quarto, knitr et le package R `KernSmooth`. Il charge également **`f.rds` et `sim_Y.rds`**, qui ne figurent pas dans l’arborescence actuelle du dépôt.

Il faut récupérer ces ressources pédagogiques autorisées et les placer à la racine avant de tenter un nouveau rendu :

```sh
quarto render BE.qmd --to html
```

Le HTML existant permet de consulter le travail sans ces fichiers. Le rendu complet n’a pas été relancé lors de cette mise à jour ; les dépendances ne sont pas verrouillées.

## Contexte

Le source conserve les consignes du cours et les réponses associées. Les résultats et comparaisons détaillés se lisent dans le document ; ce README ne constitue pas une validation indépendante des calculs.


# Detection of Biases in Film Reviews

## Présentation

Ce projet explore les biais potentiels dans les évaluations de films affichées par Fandango, en se basant sur un article du site 538 https://fivethirtyeight.com/features/fandango-movies-ratings/. L'objectif est de déterminer si les notes affichées par Fandango en 2015 étaient biaisées en faveur d'une meilleure évaluation pour augmenter les ventes de billets.

## Objectif

Le projet consiste à analyser et visualiser les données des évaluations de Fandango et de plusieurs autres plateformes (Metacritic, IMDb, Rotten Tomatoes). À l'aide des bibliothèques pandas et seaborn, nous comparons les évaluations affichées et les évaluations réelles pour voir s'il existe un écart significatif.

## Données

Deux fichiers CSV sont utilisés :
1. `fandango_scrape.csv` : Notes et étoiles affichées par Fandango.
2. `all_sites_scores.csv` : Évaluations agrégées provenant d'autres sites (IMDb, Rotten Tomatoes, Metacritic).

## Fonctionnalités

- Chargement et exploration des données.
- Analyse de la distribution des notes de Fandango par rapport aux autres plateformes.
- Visualisation des différences entre les évaluations des critiques et celles des utilisateurs sur chaque plateforme.
- Comparaison des évaluations de films sur une échelle normalisée.
- Identification des films les plus surévalués par Fandango.

## Prérequis

Les bibliothèques Python suivantes sont nécessaires pour exécuter le projet :
- numpy
- pandas
- matplotlib
- seaborn

## Utilisation

1. Clonez le dépôt : `git clone https://github.com/PRISCILLE7/Detection_of_Biases_in_Film_Reviews.git`
2. Accédez au répertoire du projet 
3. Lancez les analyses en exécutant chaque section du notebook.

## Conclusion

Les résultats indiquent que les évaluations de Fandango sont en moyenne plus élevées que celles des autres plateformes, ce qui soulève des questions quant à l'objectivité des notes affichées.

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

## Remerciements

Merci à [FiveThirtyEight](https://fivethirtyeight.com) pour l'article de référence et les données publiques.

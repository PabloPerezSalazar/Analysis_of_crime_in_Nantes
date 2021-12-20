# Analysis of crime in Nantes

### Introduction EN
Analysis of crime in Nantes (France) between 2012 and 2020 according to official records. This study includes the hypothesis of the correlation between unemployment and the crime rate.

### Objectifs de l'étude : 

1. Quels sont les crimes les plus courants.
2. Savoir comment la criminalité a évolué ces dernières années à Nantes.
3. Si la tendance se poursuit, quels sont les crimes qui connaîtront la plus forte croissance à l'avenir.
4. Est-ce qu'il a une correlation entre le crime et le chomage ?
5. Y a-t-il une corrélation entre certains délits ? (analyse factorielle)

**Sources :**

Criminalité

https://www.data.gouv.fr/fr/datasets/crimes-et-delits-enregistres-par-les-services-de-gendarmerie-et-de-police-depuis-2012/

Chomage

https://data.paysdelaloire.fr/explore/dataset/234400034_chomage-zone-t1-2003-t4-2017/table/

https://statistiques.pole-emploi.org/stmt/defm?fi=52&ss=1

Vous pouvez trouver les fichiers dans le dossier [data](https://github.com/PabloPerezSalazar/Analysis_of_crime_in_Nantes/tree/master/data)

### Approche 

Ce document présente des informations intéressantes sur la situation de la criminalité dans la ville de Nantes, en France.

Mais, deuxième objectif est de _montrer un fragment de la réalité quotidienne d'un data scientist 🐺 . 
Je voudrais montrer qu'une grande partie du travail d'un professionnel des données consiste à récupérer et à préparer des données (data wrangling)._

⚡️ Cette étude comprend également un grand nombre des principales fonctions et bibliothèques utilisées en analyse de données, telles que Pandas, Matplotlib, Scipy, Statsmodels, etc. ⚡️

### Notebooks - Python

Au [Notebook](https://github.com/PabloPerezSalazar/Analysis_of_crime_in_Nantes/blob/master/crime_analysis_Nantes.ipynb) vous pouvez trouver presque toute l'étude, y compris certaines des conclusions. 

Le code est décomposé de manière logique et commenter autant que possible.

Certains des éléments techniques que vous pouvez trouver sont :

- Comment créer un jeu de données pour chaque feuille d'un fichier Excel.

- Creation et utilisation des fonction Python dans la science des données.

- Gestion des dictionnaires. 

- Comment fitrer un dataframe.

- Concatenation de plusieurs dataframes.

- Croisement de plusieurs dataframes.

- Exporter un dataframe en csv.

- Datavisualisation avec Matplotlib et Altair

- Agregation des données.

- Transformation des données (gestion des datatypes).

- Méthode de prévision ARIMA - prévisions des séries temporelles (ML)

- Analyse de correlation de Spearman

### R - Analyse factorielle

L'analyse factorielle a été réalisée en R, afin de montrer les principales fonctions de ce grand outil statistique.

Des graphiques ont été réalisés pour tenter de trouver des relations statistiques entre les différents types de crimes.

Par exemple, si les vols sont liés à des crimes environnementaux ou non.

Les conclusions et explications se trouvent dans le document RMD.

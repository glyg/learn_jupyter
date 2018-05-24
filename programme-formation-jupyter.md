# Formation : Jupyter et python scientifique
**Baseline :** Emparez-vous de Jupyter et créez des explorations de données intéractives!

**Durée :** 3 jours

## Public visé

Cette formation s'adresse aux _data scientists_ et _data analysts_, aux développeurs souhaitant maîtriser les approches de programmation lettrées.

## Description

### Jupyter notebook

Un notebook jupyter est un document riche augmenté d'une interface de programmation. Il permet de présenter la résolution d'un problème comme **récit** intégrant description (hyper-)textuelle, code, widgets et visualisation.

Cette approche révolutionne le partage et l'exploration de données en exposant l'ensemble des composantes de l'analyse dans un cadre unifié. Les membres actuels du projet jupyter ont été récemment récompensés par
[Le prestigieux prix ACM](https://blog.jupyter.org/jupyter-receives-the-acm-software-system-award-d433b0dfe3a2).


Les technologies de l'écosystème Jupyter sont issues de la communautée python scientifique, mais incluent aujourd'hui plus d'une dizaine de langages, comme R, javascript et même C++! Un ensemble d'outils que nous explorerons accompagnent le notebook:

- Le gestionaire de paquet [`conda`](https://conda.io/docs/) facilite la distribution et la gestion des dépendances des projets de l'échosystème.

- [`nteract`](https://nteract.io/) est un client de bureau pour le notebook

- Les notebooks peuvent être accédés localement ou à distance, et [`JupyerHub`](http://jupyterhub.readthedocs.io/en/latest/) permet aisément de déployer un service multi-utlisateur.

- Le service [My binder](https://mybinder.org/) permet de mettre en ligne des notebooks exécutables dans installation de la part de l'utilisateur.

Nous illustrerons l'ensemble de ces possibilités à travers l'utilisation de python scientifique.


### Python scientifique et Pandas

Depuis une dizaine d'années, le langage python s'est imposé dans l'informatique scientifique, pour l'analyse de données, la modélisation et même le calcul formel. La communauté, qui recoupe largement la communauté Jupyter, est très active, notamment à travers les réunions PyData et les conférences SciPy ou EuroScipy. Python scientifique s'organise autour de quelques bibliothèques centrales:

- `numpy` et `scipy` fournissent les fondations du calcul scientifique: structure de données en tableau, outils d'algèbre et de statistique, etc.

- `matplotlib` est la bibliothèque de visualisation 2D historique.

- `pandas` est une bibliothèque de manipulation de données indexées permettant une manipulation rapide de données complexes.


Nous verrons comment l'interaction du notebook jupyter et des bibliothèques python scientifique permet de produire et partager une exploration intéractive des données. On insistera en particulier sur les fonctionnalités de pandas, utiles au quotidien pour l'analyste.


### 24 heures plus tard

Pour explorer nos outils, le fil rouge de cette formation sera le développement d'une simulation de la propagation d'une épidémie à travers une population. On comparera ensuite cette simulation à des données réelles issues de l'OMC sur l'épidémie annuelle de grippe.


## Pré-requis

* Ordinateur à apporter
* Avoir une première expérience en programmation
* Connaître les bases en mathématiques et statistiques

## Objectifs pédagogiques

### Administration

- Savoir installer et administrer une distribution conda.
- Mettre en ligne un notebook sur mybinder.
- Gérer le versionnage des notebooks à l'aide de `nbdime`.
- Connaître les possibilités de déploiement et de partage d'un notebook.


### Jupyter

- Maîtriser la navigation, l'exécution et l'export d'un notebook jupyter.
- Maîtriser les bases de l'écriture dans le langage à balise Markdown.
- Connaitre les bases de l'utilisation des widgets `ipywidget`.

### Python scientifique

- Savoir manipuler des données numpy.
- Savoir créer et manipuler des données avec pandas
- Connaître la création de graphiques avec matplotlib et pandas


## Méthodes pédagogiques (administratif)

On visera une alternance de 50% de travaux pratiques et 50% de cours théoriques.
Le support de cours sera fourni au format PDF accompagné d’un lien vers les supports numériques (TP & application).

## Evaluation des acquis pédagogiques (administratif)

Durant les 4 jours de formation, les TPs sont contrôlés et corrigés par le formateur.

## Programme

#### Partie 1 : Découverte du notebook

- Présentation de la communauté PyData, où chercher et où trouver de l'aide.
- Installation avec la distribution Anaconda et l'outil `conda`
- Le langage Markdown, un outil de rédaction léger et très portable
- Export de notebooks avec `nbconvert`
- Gestion de version avec `nbdime`
- `Hello World`, structure et navigation dans le notebook
- Quelques exemples de `cell magic`


#### Partie 2 : Python Scientifique

- Un bref rafraîchissment sur python
- Guide de styles, conseils d'écriture
- Les `array` Numpy : comment «vectoriser» ses calculs?
- Indexation avancée
- Scipy : calculs en tous genres
- Matplotlib : représenter des données
- Seaborn : Graphes pré-définis
- Stratégies d'optimisation: `cython` et `numba`

#### Partie 3 : Ipywidgets et interactivité

- Présentation d'Ipywidgets
- Exemples pré-définis
- Combinaisons
- Création de nouveaux widgets

#### Partie 4 : Pandas

- Structures de données :  `Series`, `DataFrame`, `Index`
- Lecture et écriture - fichiers Excel &trade;
- Affichage et inspection rapide des données
- Travailler avec des séries temporelles
- Filtres et indexage avancé
- Diviser pour mieux régner (_Split, Apply, Combine_)
- scikit-learn et pandas, introduction au machine learning


#### Partie 5 : Déploiement

- Spécification de dépendances : le fichier `environment.yml`
- MyBinder
- Création d'une image docker
- JupyterHub


## Le formateur

[Guillaume Gay](http://twitter.com/MorphoLG) développeur. Titulaire d'une thèse de physique, il travaille sur la modélisation et l'analyse de données sur des problématiques de biologies depuis 12 ans. Il a adopté python scientifique à ses débuts en 2008 et ne l'a pas quitté depuis. Guillaume a enseigné a l'université et intervient régulièrement dans des conférences, comme EuroSciPy en 2016. Ses travaux de modélisation sont publiés dans différentes revues internationales.

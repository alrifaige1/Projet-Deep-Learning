# Projet Deep Learning

## Description du projet

Ce projet a pour objectif de comparer deux approches de deep learning pour une même tâche de classification d’images : les réseaux de neurones convolutifs (CNN) et les Vision Transformers (ViT). L’idée principale est d’étudier leurs performances sur différents jeux de données spécialement conçus pour mettre en évidence leurs forces et leurs limites respectives.

Dans le cadre du projet, plusieurs datasets seront créés ou modifiés afin d’analyser le comportement des deux modèles dans différentes situations. Par exemple, certains jeux de données mettront l’accent sur la reconnaissance de textures, où les CNN sont généralement très performants grâce à leurs filtres convolutifs locaux. D’autres jeux de données demanderont de capturer des dépendances globales ou des relations à longue distance dans l’image, un domaine où les Vision Transformers peuvent être avantagés grâce au mécanisme d’attention.

Le projet comprendra l’implémentation complète des pipelines d’entraînement des deux méthodes avec une bibliothèque comme PyTorch ou TensorFlow, puis une évaluation quantitative et qualitative des résultats. Les performances seront comparées à l’aide de métriques de classification, de visualisations et d’analyses des comportements observés. Enfin, une interprétation des différences de performance permettra de mieux comprendre dans quels contextes chaque architecture est la plus adaptée.


## Environnement et exécution

Le projet a été développé dans un notebook Jupyter en Python. L’exécution a été organisée en deux étapes afin d’optimiser le développement et le temps de calcul. Dans un premier temps, le code a été exécuté sur CPU avec de petites cellules pour les tests, le débogage et la validation du pipeline. Ensuite, l’entraînement complet des modèles a été réalisé sur GPU, indispensable pour gérer efficacement la charge de calcul liée aux réseaux de neurones.

En effet, pour un projet de classification d’images avec un volume de données important, l’utilisation du GPU est fortement recommandée. Dans le cas des CNN, les performances restent correctes mais se dégradent rapidement avec la taille des datasets, tandis que les Vision Transformers (ViT) sont particulièrement coûteux en calcul en raison du mécanisme d’attention sur les patches. Ainsi, l’entraînement sur GPU devient essentiel pour réduire significativement le temps d’exécution.

Le CPU est donc principalement utilisé pour les tests rapides, la vérification du code et les mini-batches, mais il est inadapté pour un entraînement complet ou multi-epochs sur des datasets moyens à grands. Cette approche hybride CPU/GPU constitue une bonne pratique pour ce type de projet.


## Exécution du projet

Le projet est fourni sous forme de notebook Jupyter (.ipynb).

### 1. Lancer Jupyter Notebook

Dans le dossier du projet, exécuter :

jupyter notebook

Cela ouvre une interface web dans le navigateur.

### 2. Ouvrir le notebook

Cliquer sur le fichier .ipynb du projet pour l’ouvrir.

### 3. Exécuter le code
Exécuter les cellules une par une avec Shift + Entrée

Ou exécuter tout le notebook via :

Kernel → Restart & Run All 

### 4. Remarques sur l’exécution
Les premières exécutions peuvent être faites sur CPU pour tester rapidement les cellules.
L’entraînement complet des modèles est recommandé sur GPU, car il est long en CPU.
Vérifier que les dépendances Python sont installées (PyTorch / TensorFlow, numpy, matplotlib, etc.).


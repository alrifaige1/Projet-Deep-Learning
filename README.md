# Projet Deep Learning

Ce projet a pour objectif de comparer deux approches de deep learning pour une même tâche de classification d’images : les réseaux de neurones convolutifs (CNN) et les Vision Transformers (ViT). L’idée principale est d’étudier leurs performances sur différents jeux de données spécialement conçus pour mettre en évidence leurs forces et leurs limites respectives.

Dans le cadre du projet, plusieurs datasets seront créés ou modifiés afin d’analyser le comportement des deux modèles dans différentes situations. Par exemple, certains jeux de données mettront l’accent sur la reconnaissance de textures, où les CNN sont généralement très performants grâce à leurs filtres convolutifs locaux. D’autres jeux de données demanderont de capturer des dépendances globales ou des relations à longue distance dans l’image, un domaine où les Vision Transformers peuvent être avantagés grâce au mécanisme d’attention.

Le projet comprendra l’implémentation complète des pipelines d’entraînement des deux méthodes avec une bibliothèque comme PyTorch ou TensorFlow, puis une évaluation quantitative et qualitative des résultats. Les performances seront comparées à l’aide de métriques de classification, de visualisations et d’analyses des comportements observés. Enfin, une interprétation des différences de performance permettra de mieux comprendre dans quels contextes chaque architecture est la plus adaptée.


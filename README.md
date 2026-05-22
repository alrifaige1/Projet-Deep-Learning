# 🧠 Deep Learning Project – CNN vs Vision Transformers

---

## 📌 Description du projet

Ce projet a pour objectif de comparer deux approches majeures du deep learning appliquées à la classification d’images :

- les réseaux de neurones convolutifs (CNN)
- les Vision Transformers (ViT)

L’objectif est d’analyser leurs performances sur différents jeux de données afin de mettre en évidence leurs forces et leurs limites respectives.

---

### 🔬 Étude des comportements

Différents datasets sont construits ou adaptés pour tester les modèles dans des situations variées :

- **Reconnaissance de textures** → avantage des CNN grâce aux filtres locaux
- **Relations globales dans l’image** → avantage des Vision Transformers via l’attention

---

### ⚙️ Pipeline du projet

Le projet inclut :

- 🏗️ Implémentation des modèles CNN et ViT
- 📦 Construction des pipelines d’entraînement (PyTorch / TensorFlow)
- 📊 Évaluation quantitative (accuracy, loss, etc.)
- 📈 Analyse qualitative et visualisations
- 🧠 Interprétation des résultats et comparaison des architectures

---

## 🖥️ Environnement et exécution

Le projet est développé sous forme de notebook Jupyter (`.ipynb`) en Python.

### 🔁 Organisation du calcul

- 💻 **CPU** : tests, debug, validation du pipeline
- ⚡ **GPU** : entraînement complet des modèles

---

### ⚠️ Remarques importantes

- Les CNN restent exploitables sur CPU mais deviennent lents avec de gros datasets
- Les Vision Transformers sont très coûteux en calcul (attention sur patches)
- Le GPU est fortement recommandé pour les entraînements complets

---

## 🚀 Exécution du projet

### 1️⃣ Lancer Jupyter Notebook

Dans le dossier du projet :

```bash
jupyter notebook

### 2️⃣ Ouvrir le notebook

Ouvrir le fichier .ipynb du projet depuis l’interface web.

### 3️⃣ Exécuter le code
Exécuter cellule par cellule : Shift + Entrée

Ou exécuter tout le notebook :

Kernel → Restart & Run All
### 4️⃣ Dépendances nécessaires

Avant exécution, vérifier l’installation des bibliothèques :

🧠 PyTorch / TensorFlow
📊 NumPy
📈 Matplotlib
🔢 autres dépendances éventuelles
📊 Objectif final

Ce projet permet de mieux comprendre dans quels contextes :

les CNN sont les plus efficaces
les Vision Transformers surpassent les approches classiques

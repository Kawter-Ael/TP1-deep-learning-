# TP1-deep-learning-:

# Prédiction du prix des maisons avec Deep Learning (Ames Housing)

## Auteur

**Kawter Alouane**

---

# Description du projet:

Ce projet a pour objectif de construire un **modèle d’apprentissage profond (Deep Learning)** capable de **prédire le prix des maisons** à partir du dataset **Ames Housing**.

#Structure de projet :
projet/
│
├── AmesHousing.csv
├── README.md
└── tp1_DL.ipynb



Le dataset contient plusieurs caractéristiques des maisons situées à **Ames, Iowa (États-Unis)**, telles que :

* Surface du terrain
* Quartier
* Qualité générale de la maison
* Nombre de chambres
* Surface habitable
* Surface du garage
* Année de construction

L’objectif est d’utiliser ces variables pour **entraîner un réseau de neurones** capable d’estimer le **prix de vente d’une maison (SalePrice)**.

---

# Dataset

Le dataset utilisé est :

**AmesHousing.csv**

Ce fichier doit être placé dans le **dossier principal du projet**.

---

# Technologies utilisées

Ce projet utilise les bibliothèques Python suivantes :

* Python 3
* Pandas
* NumPy
* Matplotlib
* Seaborn
* TensorFlow / Keras

---

# Étapes du projet

Le projet suit les étapes principales suivantes :

1. Chargement du dataset
2. Analyse des données
3. Traitement des valeurs manquantes
4. Encodage des variables catégorielles
5. Standardisation des variables
6. Séparation des données en **train et test**
7. Construction du modèle de Deep Learning
8. Compilation du modèle avec l’optimiseur **Adam**
9. Entraînement du modèle
10. Évaluation des performances
11. Prédiction du prix des maisons

---

# Architecture du modèle :

Le modèle est un **réseau de neurones artificiel** composé de plusieurs couches :

* Couches **Dense** avec fonction d’activation **ReLU**
* Couche **Dropout** pour réduire le surapprentissage
* Couche de sortie avec **1 neurone** pour prédire le prix

Paramètres utilisés :

* Fonction de perte : **Mean Squared Error (MSE)**
* Optimiseur : **Adam**
* Métrique : **Mean Absolute Error (MAE)**

---

# Comment exécuter le projet

## 1. Cloner le dépôt

```bash
git clone https://github.com/votre-utilisateur/ames-housing-deep-learning.git
```

## 2. Accéder au dossier du projet

```bash
cd ames-housing-deep-learning
```

## 3. Installer les bibliothèques nécessaires

```bash
pip install pandas numpy matplotlib seaborn tensorflow
```

## 4. Lancer le script Python

```bash
python main.py
```

---

# Résultats

Le modèle permet de prédire le **prix des maisons** à partir des caractéristiques du dataset.

Les performances sont évaluées à l’aide de :

* **MSE (Mean Squared Error)**
* **MAE (Mean Absolute Error)**

Ces métriques permettent de mesurer l’écart entre le **prix réel** et le **prix prédit** par le modèle.

---

# Améliorations possibles

Plusieurs améliorations peuvent être apportées au projet :

* optimisation des hyperparamètres
* sélection de variables plus pertinente
* validation croisée
* utilisation d’architectures de réseaux plus avancées
* ajout de visualisations des résultats



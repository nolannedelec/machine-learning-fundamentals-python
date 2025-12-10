# Machine Learning Fundamentals (Portfolio Scikit-Learn)

> **Collection d'implémentations de référence** couvrant les algorithmes fondamentaux de l'Apprentissage Automatique (Supervisé & Non-Supervisé).

Ce dépôt regroupe une série de notebooks Jupyter réalisés pour maîtriser les bases théoriques et pratiques du Machine Learning. Chaque projet aborde une problématique classique (Régression, Classification, Clustering) avec une approche rigoureuse : préparation des données, modélisation, optimisation et visualisation.

---

### Contenu du Portfolio

#### 1. Régression : Prédiction Immobilière (`01_housing_price_regression.ipynb`)
* **Objectif :** Prédire le prix médian des logements (Housing Dataset).
* **Concepts :** Nettoyage de données (Data Cleaning), Validation Croisée (Cross-Validation), Recherche d'hyperparamètres (**GridSearch**).
* **Modèle :** Régression Linéaire & Polynomiale.

#### 2. Classification : Reconnaissance de Chiffres (`02_mnist_classification_svm.ipynb`)
* **Objectif :** Classifier des chiffres manuscrits du dataset **MNIST**.
* **Concepts :** Support Vector Machines (**SVM**), Régression Logistique, Matrices de confusion, Métriques (Précision/Rappel/F1-Score).
* **Résultat :** Taux de classification > 92%.

#### 3. Clustering : Segmentation de Visages (`03_faces_clustering_kmeans.ipynb`)
* **Objectif :** Regrouper des visages similaires sans étiquettes (Dataset Olivetti Faces).
* **Concepts :** Apprentissage non-supervisé, Algorithme **K-Means**.
* **Visualisation :** Affichage des centres de clusters (visages moyens).

#### 4. Réduction de Dimension (`04_pca_dimensionality_reduction.ipynb`)
* **Objectif :** Compresser et visualiser des données complexes en 2D/3D.
* **Concepts :** Analyse en Composantes Principales (**PCA**), Variance expliquée, Projection de données.
* **Application :** Accélération de l'apprentissage sur MNIST tout en conservant 95% de l'information.

---

### Stack Technique

| Catégorie | Outils |
| :--- | :--- |
| **Langage** | ![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white) |
| **ML & Data** | ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) |
| **Visualisation** | `Matplotlib` `Seaborn` |
| **Environnement** | `Jupyter Notebook` |

---

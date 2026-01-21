# 🐧 Penguin Species Segmentation - K-Means Clustering

## 📌 Présentation
Ce projet explore l'apprentissage non-supervisé en utilisant l'algorithme **K-Means**. L'enjeu est de découvrir des structures cachées dans un jeu de données biologiques sans connaître les catégories à l'avance.

## 🛠️ Stack Technique
* **Algorithme :** K-Means Clustering.
* **Méthodologie :** Elbow Method (Méthode du coude) pour l'optimisation de 'k'.
* **Dataset :** Palmer Penguins (via Seaborn).

## 📊 Analyse des Résultats
* **Nombre de clusters :** 3 (identifié via le graphique d'inertie).
* **Segmentation :** Le modèle a réussi à séparer distinctement les manchots de grande taille (poids élevé) de ceux ayant des becs plus longs ou des gabarits plus petits.
* **Validation :** Les centroïdes calculés correspondent aux moyennes morphologiques des trois espèces réelles présentes dans le dataset.

## 📁 Fichiers
* `Clustering_Segmentation.ipynb` : Analyse complète et visualisations.

---
*Projet réalisé par Yacine YEFSAH - Étudiant en M1 SAAD, Université de Caen Normandie.*

# 📊 Customer Churn Analysis Dashboard

## 📝 Résumé du projet
- **Situation** : Analyse des raisons du churn (attrition) des clients pour identifier les tendances démographiques et comportementales, ainsi que les faiblesses dans l'offre de l'entreprise.
- **Mission** : Créer un tableau de bord interactif pour visualiser les raisons principales du churn, les segments démographiques les plus affectés et les opportunités d'amélioration.
- **Objectifs** :
  1. Préparer les données pour garantir des analyses fiables et cohérentes.
  2. Identifier les raisons principales du churn et les segments de clientèle les plus à risque.
  3. Concevoir un tableau de bord interactif pour simplifier l'interprétation des données.

---

## 🖼 Résultat visuel
Voici une capture d’écran du tableau de bord final réalisé dans Excel :

![Capture d'écran Customer Churn Analysis Dashboard](https://github.com/Arnaudl44/Excel-Projects/blob/main/Customer%20Churn%20Analysis/images/Capture%20d'%C3%A9cran_Customer_Churn_Analysis.png?raw=true)

---

## 📂 Étapes du projet

### 1. Préparation des données 
- **Nettoyage des données** : 
  - Suppression des doublons et des valeurs aberrantes.
- **Ajout de colonnes calculées** :
  - `Churn Rate` : taux d'attrition calculé comme le pourcentage de clients churnés.
  - **Segmentation démographique** : création de groupes d’âge (`19-28`, `29-38`, etc.).
  - **Raisons du churn** : regroupement en catégories (`Service Issues`, `Pricing`, `Competitor Offers`).

### 2. Analyse des données 
- **Analyse des raisons du churn** :
  - Identification des raisons principales comme le prix ou les offres concurrentes.
  - Calcul des proportions de churn pour chaque catégorie.
- **Analyse démographique** :
  - Exploration du churn par groupe d’âge (clients jeunes, seniors).
  - Segmentation par caractéristiques démographiques (`Intl Plan`, `Contract Type`).
- **Analyse de la consommation** :
  - Exploration des habitudes de consommation (`Unlimited Plan`, consommation de données).
  - Identification des corrélations avec le churn.

---

## 📊 Insights

- **Taux d'attrition global :**
  - 26,86 % des clients ont churné.

- **Raisons principales du churn :**
  - La compétition est un facteur majeur avec 37 % des clients indiquant que la concurrence offre de meilleures solutions.
  - Les problèmes de service représentent une part significative, notamment des attitudes perçues comme négatives envers le support client.

- **Analyse démographique :**
  - Les clients de moins de 30 ans représentent 29 % du churn total, mais les seniors (44 %) sont le groupe le plus affecté.
  - Les États comme la Californie (75 %) et l’Indiana (66,67 %) ont les taux de churn les plus élevés.

- **Analyse par consommation et plan :**
  - Les clients ayant un plan limité (moins de 5 Go) sont plus enclins à churner.
  - Les clients avec des plans illimités présentent un churn plus faible, suggérant l’intérêt d’améliorer les offres pour ces utilisateurs.

- **Analyse par secteur :**
  - Les États avec des offres compétitives (Californie, New York) présentent des taux de churn élevés, soulignant la nécessité de différencier l'offre.

---

## 🛠️ Étapes techniques principales
- **Tableaux croisés dynamiques (TCD)** :
  - Groupement des données pour analyser les raisons du churn, les groupes d’âge et les segments démographiques.
  - Visualisation des proportions de churn à l'aide de regroupements personnalisés.
- **Ajout de colonnes personnalisées** :
  - Création de catégories pour les raisons du churn (ex : `Competitor Made Better Offer` → `Competitor Offers`).
  - Conversion des données brutes en insights actionnables.
- **Graphiques interactifs** :
  - Utilisation de graphiques empilés, en anneau et combinés pour une lecture rapide.
  - Carte de chaleur pour visualiser les taux de churn par État.

---

## 📄 Fichier Excel principal
- **Nom** : `Customer_Churn_Analysis.xlsx`
- **Description** : Tableau de bord interactif pour analyser les raisons du churn et identifier les segments à risque.
- **Lien** : [Télécharger le fichier Excel](https://github.com/Arnaudl44/Excel-Projects/blob/main/Customer%20Churn%20Analysis/files/Customer_Churn_Analysis.xlsx).

---

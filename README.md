# Analyse des Tendances du Bonheur Mondial (2015-2024)

Ce projet vise à explorer les tendances du bonheur mondial sur une décennie (2015-2024) en s'appuyant sur les données du **World Happiness Report**. Il s'intéresse aux facteurs économiques, sociaux et personnels influençant le bien-être des populations, et propose des visualisations et des analyses pour aider à mieux comprendre ces dynamiques.

## Contexte

Les indices de bonheur, publiés chaque année dans le **World Happiness Report**, reflètent le niveau de satisfaction des populations à travers plusieurs variables clés : PIB par habitant, soutien social, espérance de vie en bonne santé, perception de la corruption, générosité et liberté de choix. Ce projet ambitionne d'extraire des tendances, d'identifier les corrélations majeures et de proposer des insights utiles pour les décideurs.

---

## Objectifs

- **Nettoyage des Données** : Assurer la cohérence et la qualité des données (suppression des doublons, gestion des valeurs manquantes, etc.).
- **Analyse des Facteurs Clés** : Comprendre l'impact de variables comme le PIB, le soutien social et la santé sur le bonheur.
- **Visualisation des Résultats** : Créer des tableaux de bord interactifs avec Power BI.
- **Propositions Pratiques** : Identifier des pistes d'amélioration pour les politiques publiques visant à renforcer le bien-être des populations.

---

## Livrables

1. **Dataset Nettoyé** : Un fichier CSV consolidé et prêt pour l'analyse.
2. **Visualisations** : Tableaux de bord interactifs sous Power BI pour explorer les tendances globales et régionales.

---

## Structure du Projet

- **`Cahier des Charges world happiness.docx`** : Document décrivant les objectifs et le cadre du projet.
- **`world_happiness.csv`** : Données brutes provenant du World Happiness Report.
- **`world_happiness_Cleaning.csv`** : Fichier nettoyé et formaté pour l'analyse.
- **`world_happiness.ipynb`** : Notebook Jupyter pour le traitement et l'analyse des données.
- **`world_happiness.pbix`** : Tableau de bord interactif Power BI.

---

## Méthodologie

### 1. Nettoyage des Données
- Outils : Python (pandas, numpy) et Power Query.
- Étapes :
  - Gestion des valeurs manquantes et des doublons.
  - Standardisation des formats (dates, chiffres, textes).
  - Fusion des données de plusieurs années (2015-2024) en un seul dataset.

### 2. Analyse et Visualisation
- Outils :
  - **Python** : Pour les analyses exploratoires (corrélations, statistiques descriptives).
  - **Power BI** : Pour des visualisations interactives.
- Analyses principales :
  - Étude des corrélations entre les scores de bonheur et les variables clés.
  - Comparaison des scores entre les pays, régions et années.
  - Identification des tendances majeures.

---

## Comment Exécuter le Projet

1. Clonez le dépôt GitHub :
   ```bash
   git clone https://github.com/AnassMtere/World-Happiness-Analysis.git

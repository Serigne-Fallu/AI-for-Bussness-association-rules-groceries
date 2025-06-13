# 🛒 Exploration des Règles d'Association avec R

**Optimiser l’expérience client grâce à l’analyse des comportements d’achat.**

---

## 📌 Contexte

Pourquoi, après un achat en ligne, reçoit-on des recommandations du type *« les clients ont aussi acheté... »* ?  
Et si vous êtes commerçant, comment pouvez-vous personnaliser vos recommandations ou créer des offres ciblées ?

Ce projet explore **l’extraction de règles d’association** pour répondre à ces enjeux, en identifiant les produits fréquemment achetés ensemble à partir de données réelles de transactions.

---

## 🧾 Jeu de données

- **Nom** : `Groceries`
- **Source** : Ensembles de transactions de ventes au détail
- **Taille** : 9 836 transactions
- **Format** : Matrice binaire (transactions × items)

---

## 🎯 Objectifs

- Identifier les **items fréquemment achetés ensemble**
- Générer des **règles d’association** fiables (de type *si A alors B*)
- **Cibler des produits spécifiques** pour guider des stratégies marketing
- Visualiser les résultats de façon lisible et exploitable

---

## 🛠️ Méthodes et outils

- **Langage** : `R`
- **Packages** : `arules`, `arulesViz`, `tidyverse`
- **Techniques** :
  - Exploration des données
  - Extraction d’**itemsets fréquents**
  - Génération de **règles d’association** (support, confiance, lift)
  - **Filtrage ciblé** d’articles
  - Visualisation : graphes, matrices, réseaux

---

## 📊 Étapes de l’analyse

1. 📂 Chargement et exploration des données  
2. 📌 Extraction des itemsets fréquents (`apriori`)  
3. 📐 Création de règles d’association pertinentes  
4. 🎯 Ciblage d’articles spécifiques (ex : « whole milk »)  
5. 📈 Visualisation : graphe réseau, scatterplot, grouped matrix

---

## 📁 Structure du dépôt


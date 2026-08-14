# 🛒 E-Commerce Dashboard — Power BI

## 📊 Présentation

Ce projet consiste à analyser la performance commerciale
d'une entreprise e-commerce à travers un dashboard Power BI
interactif.

L'objectif est d'identifier les principaux leviers de chiffre
d'affaires, de rentabilité et de performance commerciale.

---

## 🎯 Problématique

- Comment évolue le chiffre d'affaires ?
- Quelles catégories génèrent le plus de revenus ?
- Quels produits sont les plus performants ?
- Quels segments clients contribuent le plus au CA ?
- Quelles catégories présentent les meilleures marges ?
- Comment évoluent les performances par rapport à N-1 ?

---

## 🛠️ Technologies

- Power BI
- DAX
- Power Query
- Modélisation dimensionnelle
- Star Schema

---

## 🧱 Modélisation

Le modèle repose sur une architecture en étoile :

FactSales
→ DimDate
→ DimCustomer
→ DimProduct
→ DimLocation
→ DimShipping

![Data_Model](Data_Model/Data_Model.PNG)

---

## 📈 Dashboard

![Dashboard](Dashboard/Dashboard.PNG)

### Principaux indicateurs

- Chiffre d'affaires
- Nombre de commandes
- Nombre de clients
- Panier moyen
- Marge %
- Evolution du CA vs N-1

---

## 🧮 DAX

La documentation complète des mesures DAX utilisées dans le dashboard est disponible dans le dossier [**Mesures DAX**](Mesures/README_Mesures_DAX.md).


## 📂 Données

Source :

Superstore Dataset — Kaggle ([Voir le dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final))

---

## 💡 Insights

Le dashboard permet d'identifier les principales tendances et leviers de performance à travers l'analyse du chiffre d'affaires, de la rentabilité, des commandes et du comportement client.

Les principaux insights portent notamment sur :

- 📈 l'évolution des KPI par rapport à l'année précédente ;
- 💰 l'analyse du chiffre d'affaires et de la rentabilité ;
- 🛒 l'évolution du panier moyen et du volume de commandes ;
- 👥 la dynamique du nombre de clients ;
- 🏆 l'identification des catégories, segments et zones géographiques les plus performants ;
- ⚠️ la détection des variations et points d'attention nécessitant une analyse approfondie.

Les indicateurs et visualisations du dashboard permettent ainsi de transformer les données en **insights exploitables pour orienter le pilotage de la performance commerciale**.

---

## 👤 Auteur

Ahmed Zouaghi

Master 2 SIAD — Business Intelligence
Université de Lille

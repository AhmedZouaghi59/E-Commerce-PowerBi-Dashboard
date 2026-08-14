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

Les principales mesures DAX utilisées sont disponibles
dans le dossier `/dax`.

---

## 📂 Données

Source :

Superstore Dataset — Kaggle ([Voir le dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final))

---

## 💡 Insights

Les principales conclusions de l'analyse sont présentées
directement dans le dashboard.

---

## 👤 Auteur

Ahmed Zouaghi

Master 2 SIAD — Business Intelligence
Université de Lille

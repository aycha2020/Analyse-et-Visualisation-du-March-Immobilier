# Analyse-et-Visualisation-du-March-Immobilier

#  Projet Business Intelligence Immobilier – Maroc

##  Présentation du Projet

Ce projet a pour objectif d’analyser le marché immobilier marocain à travers une approche **Business Intelligence (BI)**.

L’objectif principal est de transformer des données brutes d’annonces immobilières en informations exploitables grâce à :
- l’ingénierie des données,
- la modélisation décisionnelle,
- l’analyse de données,
- et la visualisation interactive avec **Power BI**.

Le projet permet d’explorer :

- L’évolution des prix immobiliers
- Les différences de prix entre les villes
- Les zones les plus chères et les moins chères
- Le prix moyen au mètre carré
- La répartition géographique des annonces
- Les tendances du marché immobilier

---

##  Projet Associé – Collecte des Données

Ce projet BI est basé sur un projet précédent de **web scraping immobilier**, où les données ont été collectées depuis **Avito Maroc** à l’aide de **Python et Selenium**.

##### Projet Scraping :  
[Projet Scraping Immobilier](https://github.com/aycha2020/Scraping)

---

##  Technologies Utilisées

### Collecte et Préparation des Données
- Python
- Selenium
- BeautifulSoup
- Pandas

### Base de Données & Stockage
- PostgreSQL
- SQL
- Docker

### Business Intelligence
- Power BI
- DAX
- Modélisation de données

---

##  Architecture du Projet

```text
Scraping Web (Avito Maroc)
            ↓
Nettoyage & Transformation des données
            ↓
Base de données PostgreSQL
            ↓
Modélisation Power BI
            ↓
Création de Dashboards interactifs
            ↓
Analyse & Aide à la décision

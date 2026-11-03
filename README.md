# 🛡️ Projet Data Engineering de bout en bout avec Microsoft Fabric : Insurance Analytics

Projet complet de data engineering sur **Microsoft Fabric** : des données brutes d'assurance sont ingérées, stockées, nettoyées, transformées, puis exposées dans un **tableau de bord Power BI** pour produire des analyses métier.

---

## 📌 Présentation

Ce projet montre comment construire une solution de data engineering complète avec Microsoft Fabric, de l'ingestion des données jusqu'à la visualisation.

Plutôt que d'apprendre chaque composant Fabric séparément, ce projet réunit tout le flux de travail : **Data Pipeline → OneLake → Lakehouse → PySpark → Power BI**.

---

## 🏗️ Architecture et flux du projet

```
Données sources
      ↓
Pipeline de données Microsoft Fabric
      ↓
OneLake
      ↓
Lakehouse
      ↓
Transformation PySpark
      ↓
Données curatées (prêtes pour l'analyse)
      ↓
Visualisation Power BI
      ↓
Informations métier (business insights)
```

> 💡 Ajoutez ici un schéma d'architecture : `docs/architecture.png`

---

## 🎯 Ce que vous allez construire

- Un projet de data engineering de bout en bout sur Microsoft Fabric
- Un projet d'analyse de données d'assurance
- Un pipeline de données Microsoft Fabric
- Un stockage de données dans OneLake
- Un Lakehouse Fabric
- Des transformations de données avec PySpark
- L'ingestion et le traitement des données
- Le nettoyage et la transformation des données
- Des données prêtes pour l'analyse
- Un tableau de bord Power BI
- Un flux de travail réaliste de data engineering

---

## 🛠️ Technologies utilisées

| Catégorie | Outils |
|---|---|
| Plateforme | Microsoft Fabric |
| Orchestration / ingestion | Fabric Data Factory, Data Pipelines |
| Stockage | OneLake, Lakehouse |
| Traitement | Apache Spark, PySpark |
| Langages | Python, SQL |
| Visualisation | Power BI |

---

## 📊 Cas d'usage : Insurance Analytics

Le projet exploite des données d'assurance (par exemple [polices, clients, sinistres, primes : à adapter à votre jeu de données]) et les transforme en indicateurs exploitables, tels que :

- [Nombre de sinistres par période / par type]
- [Montant total des primes et des remboursements]
- [Ratio sinistres/primes]
- [Répartition par région, produit ou profil client]

---

## 🔄 Étapes du projet

1. **Ingestion** : un pipeline Fabric Data Factory copie les données sources vers OneLake.
2. **Stockage** : les données brutes sont enregistrées dans le Lakehouse (zone *raw*).
3. **Nettoyage** : avec PySpark, traitement des valeurs manquantes, des doublons et des types de données.
4. **Transformation** : jointures, calculs et agrégations pour produire des tables curatées.
5. **Mise à disposition** : les tables prêtes pour l'analyse sont exposées dans le Lakehouse.
6. **Visualisation** : création du rapport et du tableau de bord Power BI.
7. **Analyse** : lecture des indicateurs et des enseignements métier.

---

## 📁 Structure du dépôt

```
.
├── data/                 # Échantillons de données sources
├── notebooks/            # Notebooks PySpark (nettoyage, transformation)
├── pipelines/            # Définitions / captures des pipelines Fabric
├── powerbi/              # Fichier .pbix ou captures du tableau de bord
├── docs/                 # Schémas d'architecture et captures d'écran
└── README.md
```

> À adapter selon l'organisation réelle de votre projet.

---

## 🚀 Prérequis et mise en route

**Prérequis**
- Un compte Microsoft avec accès à **Microsoft Fabric** (licence d'essai possible)
- Un espace de travail (*workspace*) Fabric avec une capacité activée
- Power BI Desktop (optionnel, pour modifier le rapport)

**Étapes**
1. Cloner le dépôt :
   ```bash
   git clone [URL-de-votre-depot]
   ```
2. Créer un workspace Fabric et un **Lakehouse**.
3. Importer les notebooks du dossier `notebooks/` dans le workspace.
4. Configurer et lancer le **Data Pipeline** pour ingérer les données.
5. Exécuter les notebooks PySpark dans l'ordre.
6. Ouvrir le rapport Power BI et le connecter au Lakehouse.

---

## 📸 Aperçu

> Ajoutez ici des captures d'écran : pipeline, Lakehouse, notebook, tableau de bord Power BI.

---

## 🎓 Ce que vous allez apprendre

- Data engineering sur Microsoft Fabric
- Data Pipelines Microsoft Fabric
- OneLake et Lakehouse
- PySpark
- Ingestion, nettoyage et transformation des données
- Architecture Data Lakehouse
- Pipelines ETL / ELT
- Visualisation avec Power BI

---

## 👨‍💻 À qui s'adresse ce projet ?

- Aspirants data engineers
- Data engineers Microsoft Fabric et Azure
- Data engineers cloud
- Débutants en data engineering
- Développeurs qui se reconvertissent vers la data
- Analystes de données qui découvrent Microsoft Fabric
- Toute personne qui cherche un projet Fabric réaliste

---

## 🎥 Tutoriel vidéo

[Lien vers la vidéo YouTube]

---

## 🤝 Contribution

Les suggestions et améliorations sont les bienvenues : ouvrez une *issue* ou une *pull request*.

## 📄 Licence

[MIT / autre : à préciser]

## 📬 Contact

Mariem Kbaier

---

`#MicrosoftFabric` `#DataEngineering` `#OneLake` `#Lakehouse` `#PySpark` `#PowerBI` `#InsuranceAnalytics` `#ETL`

# Projet-Data-Engineering-
# Contexte :
Dans le cadre de ce projet de data engineering sur le cloud, notre mission a été de concevoir une infrastructure robuste, scalable et sécurisée, capable de collecter, stocker, transformer, modéliser et visualiser des données médicales hétérogènes issues d’un environnement hospitalier simulé.
Nous avons mis en place une architecture cloud-native complète sur Microsoft Azure, s’appuyant sur le modèle Lakehouse et le framework ELT, en exploitant des technologies modernes pour automatiser l’ingestion, le traitement et l’analyse des données à des fins décisionnelles.
# Objectifs du projet :
- Créer un pipeline de traitement de données structuré autour des couches Bronze, Silver et Gold
- Nettoyer, enrichir et standardiser des données hospitalières simulées Réaliser des agrégations et extractions de KPI médico-financiers - Mettre en place un data model en étoile dans Azure Synapse Automatiser l’exécution des traitements avec Azure Data Factory Construire des dashboards cliniques interactifs avec Power BI
# Jeu de données utilisé :
- Nom : MedSynora – Medical Data Warehouse Provenance : Kaggle
- Contenu : données simulées sur l’année 2024 incluant les patients, consultations, diagnostics, traitements, coûts, signes vitaux, etc.
# Technologies utilisées :
- Cloud & Stockage : Azure Data Lake Storage Gen2 (ADLS)
- Traitement & Ingestion : Azure Databricks (PySpark), GitLab API
- Orchestration : - Azure Data Factory
- Modélisation : Azure Synapse Analytics (modèle en étoile) Visualisation : Power BI connecté à Synapse Serverless
- Sécurité : IAM, Managed Identity, Chiffrement AES-256

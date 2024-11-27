# Data Management and Analytics Solution with Azure

💡 Ce projet vise à concevoir une solution complète pour l'intégration et le traitement des données. Les tables issues d'une base de données **SQL Server locale** sont d'abord ingérées à l'aide d'**Azure Data Factory**, puis stockées dans **Azure Data Lake**. Ensuite, **Azure Databricks** est utilisé pour transformer les données brutes en une forme propre et optimisée. Les données nettoyées sont ensuite chargées dans **Azure Synapse Analytics**. Enfin, **Microsoft Power BI** est intégré à **Azure Synapse Analytics** pour créer un tableau de bord interactif. Par ailleurs, **Azure Active Directory (AAD)** et **Azure Key Vault** sont utilisés pour assurer la gouvernance et la surveillance du projet.

## 📖 Table des matières
- [Introduction](#introduction)
- [Architecture](#architecture)
- [Technologies utilisées](#technologies-utilisées)
- [Ingestion des données](#ingestion-des-données)
- [Traitement des données](#traitement-des-données)
- [Conclusion](#conclusion)

## Introduction
Ce projet a pour objectif de créer une solution de traitement de données complète, allant de l’ingestion à la visualisation interactive des données. Il s’agit d’un pipeline de données moderne utilisant les outils de la plateforme Microsoft Azure pour automatiser et optimiser les processus de collecte, de transformation et d'analyse.

## Architecture
![image](https://github.com/user-attachments/assets/6b310dae-9056-4e9b-a2c6-587912463414)

L'architecture du projet se compose des éléments suivants :
- **Azure Databricks :** Utilisé pour le traitement, la transformation et l’analyse des données. Il fournit un environnement collaboratif et interactif pour exécuter des tâches basées sur Spark.
- **Azure Data Factory :** Gère et orchestre le flux de travail des données. Il est responsable de l'ingestion des données à partir de diverses sources, de la transformation des données et de la planification des tâches.
- **Azure Storage :** Sert de lac de données pour stocker les données brutes et traitées. Il peut également héberger les résultats intermédiaires générés lors de l'analyse.
- **Azure Data Lake Storage Gen2 :** Stocke les données nettoyées et transformées, les rendant accessibles pour la visualisation et les rapports.
- **Azure Power BI :** Se connecte à la base de données Azure SQL pour créer des tableaux de bord interactifs et visuellement attrayants pour l'exploration des données.

## Technologies utilisées:
- Azure Databricks
- Azure Data Factory
- Azure Data Lake Storage
- Azure Synapse Analytics
- Azure Power BI
- Azure Key Vault
- Azure Active Directory
- Microsoft SQL Server
- PySpark
- SQL

![image](https://github.com/user-attachments/assets/6c69111e-d745-49af-969f-b601aab49ea3)

## Ingestion des données:

![image](https://github.com/user-attachments/assets/9d5e0149-29a8-4f19-bb5d-7938533435d1)

## Traitement des données: 

![image](https://github.com/user-attachments/assets/9386ae1f-254a-419a-a136-d0da0748f34b)

L'étape de traitement des données consiste à nettoyer et transformer les données brutes en un format structuré adapté à l'analyse. Cette étape tire parti des capacités de calcul distribué d'Azure Databricks pour un traitement efficace.

## Conclusion:

🚀 Le projet d'analyse des données sur Azure montre comment exploiter les services Azure pour traiter, analyser et visualiser des données à grande échelle. En suivant les configurations et les guides fournis dans ce dépôt, vous pouvez adapter le projet à d'autres domaines et étendre ses fonctionnalités. Bonne analyse des données !

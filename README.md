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

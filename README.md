# Analyse-en-Temps-Reel-des-Donnees-du-Marche-Boursier-Utilisant-Kafka

## Introduction

Ce projet vise à réaliser une analyse en temps réel des données du marché boursier grâce à Kafka.

## Technologies Utilisées

- **Langage de Programmation** : Python
- **Services Amazon Web Service (AWS)** :
  - S3  pour le stockage des données
  - Athena pour les requêtes SQL sur des données stockées sur S3
  - Glue Crawler pour le catalogage des données
  - Glue Catalog comme référentiel central pour les métadonnées
  - EC2 pour l'exécution de nos applications
- **Apache Kafka** pour le traitement des flux de données

## Architecture

![Architecteur](https://github.com/RachidDay/Analyse-en-Temps-Reel-des-Donnees-du-Marche-Boursier-Utilisant-Kafka/assets/93099244/d1dbb284-5102-4438-85a2-f8944c74ee5d)



## Mise en Œuvre
Le projet est structuré comme suit :
1. **Ingestion des Données** : Les données du marché boursier sont captées en temps réel via Kafka.
2. **Traitement des Données** : Les données sont traitées et éventuellement transformées pour faciliter l'analyse.
3. **Stockage des Données** : Les données traitées sont stockées de manière sécurisée sur AWS S3.
4. **Analyse des Données** : Les données stockées sont analysées en utilisant AWS Athena et les résultats sont catalogués via AWS Glue.


## Contact
Pour toute question, veuillez me contacter à dayrachid20@gmail.com.

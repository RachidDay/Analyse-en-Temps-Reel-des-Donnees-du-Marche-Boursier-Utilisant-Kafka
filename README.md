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
L'architecture du projet est conçue pour être robuste et évolutive. Elle permet une ingestion efficace des données en flux continu, un traitement intermédiaire (si nécessaire) et une analyse en aval pour extraire des informations pertinentes.

![Architecture](Architecture.jpg)

## Mise en Œuvre
Le projet est structuré comme suit :
1. **Ingestion des Données** : Les données du marché boursier sont captées en temps réel via Kafka.
2. **Traitement des Données** : Les données sont traitées et éventuellement transformées pour faciliter l'analyse.
3. **Stockage des Données** : Les données traitées sont stockées de manière sécurisée sur AWS S3.
4. **Analyse des Données** : Les données stockées sont analysées en utilisant AWS Athena et les résultats sont catalogués via AWS Glue.

## Contribution
Les contributions à ce projet sont les bienvenues. Vous pouvez contribuer en :
- Améliorant le code d'ingestion ou de traitement des données.
- Proposant des analyses plus approfondies ou des méthodes de visualisation.
- Optimisant l'infrastructure AWS pour des performances accrues.

## Licence
Ce projet est distribué sous licence [insérer la licence appropriée ici]. Veuillez voir le fichier LICENSE pour plus d'informations.

## Contact
Pour toute question, veuillez me contacter à dayrachid20@gmail.com.

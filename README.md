# POEI-DevOps
projet Zenika

Prérequis nécessaires :

Compte github : https://github.com/khun1964/POEI-DevOps

Compte Google Cloud Platform

Dossier Visual Studio Code dédié : POEI Project

Google Cloud Platform:
Pour la Scalibilité : 
Création de kubernetes Clusters   : réaliser via GCP
Usage apply Kubernetes :est ce nécessaire non !
Backup for GKE (requis) : réaliser



Création d'un instance-poei pour une BDD Mysql avec backend recommandé : réaliser

Réalisation dans GCP au plus tard 12h00 du 10-07-2023 : réaliser

Le cluster kubernetes qualification via un fichier yaml sera dupliqué pour réaliser le cluster préprod qui lui même sera cloné vers un cluster prod. 

Visual Studio Code: installer la configuration Java 

Rapatriement du Code qui est un projet en Java 17 du dépôt github : https://github.com/Riduidel/spring-petclinic-microservices 
vers le mien de manière automatique: Compte github : https://github.com/khun1964/POEI-DevOps.      : réaliser

Github-actions à automatiser si possible! : githubactions:worflow à réaliser
Fin PM 10-07-2023

Structuration prévisionnelle :

Trois dockerfiles doîvent être fournies :  qualification / La préprod / La Prod/   : forunis PM 10 07 2023

usage de Kubernettes, donc fichier yaml pour chaque déploiements  :à réaliser

Usage de Terraform pour le tout! PB de paramétrage à régler 11 07 2023 

Testing Prometheus & Grafana  pour 12 07 2023

Mardi instalation et déploiment prévu environnemnt qualification puis les deux autres.

Mercredi déploiements complets et crash test de la prod : 

Choix de la BDD : le calcul de l"ensemble pour 100 000 utilisateurs +- 61 Mo de données : Mysql bdd dans GCP avec Backup
Celles-ci doivent être accessible mais sécurisées.



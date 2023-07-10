# POEI-DevOps
projet Zenika

Prérequis nécessaires :

Compte github : https://github.com/khun1964/POEI-DevOps

Compte Google Cloud Platform

Dossier Visual Studio Code dédié : POEI Project

Google Cloud Platform:
Pour la Scalibilité : 
Création de kubernetes Clusters   
            Usage apply Kubernetes doivent 
            Backup for GKE (requis)

Le cluster kubernetes qualification via un fichier yaml sera dupliqué pour réaliser le cluster préprod qui lui même sera cloné vers un cluster prod. 

Création d'un instance-poei pour une BDD Mysql avec backend recommandé.

Réalisation dans GCP au plus tard 12h00 du 10-07-2023.

Visual Studio Code: installer la configuration Java 

Rapatriement du Code qui est un projet en Java 17 du dépôt github : https://github.com/Riduidel/spring-petclinic-microservices 
vers le mien de manière automatique: Compte github : https://github.com/khun1964/POEI-DevOps.

Github-actions à automatiser si possible!
Fin PM 10-07-2023

Structuration prévisionnelle :

Trois dockerfiles doîvent être fournies :  qualification / La préprod / La Prod/

usage de Kubernettes, donc fichier yaml pour chaque déploiements.

Usage de Terraform pour le tout!

Testing Prometheus & Grafana
Mardi instalation et déploiment prévu environnemnt qualification puis les deux autres.

Mercredi déploiements complets et crash test de la prod : 

Choix de la BDD : le calcul de l"ensemble pour 100 000 utilisateurs +- 61 Mo de données.
Celles-ci doivent être accessible mais sécurisées.



# POEI-DevOps
projet Zenika

Prérequis nécessaires :

Compte github : https://github.com/khun1964/POEI-DevOps

Compte Google Cloud Platform

Dossier Visual Studio Code dédié : POEI Project


Google Cloud Platform:

Création d'une instance test : instance-poei
Création de kubernetes Clusters
            Usage apply Kubernetes
            Backup for GKE (requis)


Visual Studio Code:

Rapatriement du Code qui est un projet en Java 17, configuration VCS.



Structuration prévisionnelle :

Trois dockerfiles pour trois conteneurs de déploiements :  qualification / La préprod / La Prod/

usage de Kubernettes, donc fichier yaml pour chaque déploiements.


Usage de Terraform pour le tout!

Testing Prometheus & Grafana


Choix de la BDD : le calcul de l"ensemble pour 100 000 utilisateurs +- 61 Mo de données.
Celles-ci doivent être accessible mais sécurisées.

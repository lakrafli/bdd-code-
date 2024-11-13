
## **Migration de la Base de Données vers Redis et MongoDB**
## Objectif

Ce projet vise à migrer une base de données existante vers deux technologies NoSQL : Redis et MongoDB. La migration se fait en deux étapes : la première avec Redis, suivie de l'intégration avec MongoDB. L'objectif est d'optimiser la gestion et les performances des données en utilisant ces technologies adaptées.
Déroulement du Projet

    Installation de Redis localement

    Configuration de l'environnement Python pour Redis

    Migration des données vers Redis

    Exécution des requêtes Redis spécifiées par le client

    Fusion des données en format JSON pour les manipulations nécessaires

## **Résultats##

    Amélioration des performances : Les tests de performance révèlent des gains significatifs dans les temps de réponse des requêtes grâce à l'utilisation de Redis pour la gestion des données.

Technologies Employées

    Redis : Base de données NoSQL utilisée pour le stockage rapide des données en mémoire.
    Python : Langage de programmation utilisé pour interagir avec Redis et MongoDB.
    JSON : Format léger et structuré pour le stockage et l'échange de données.

## **Installation des Dépendances

Pour installer les bibliothèques nécessaires, exécute la commande suivante :

pip install redis pymongo

Lancer le Programme

Une fois les dépendances installées, lance le script avec cette commande :

python script.py

## **Structure du Projet

    bddPilotes/ : Contient les fichiers .txt pour l'importation des données.
    venv/ : Dossier de l'environnement virtuel Python.
    fichiers.py : Scripts Python pour la conversion des données et l'intégration avec Redis et MongoDB.
    README.md : Documentation détaillée du projet (ce fichier).

## **Auteurs

Ce projet a été réalisé par Lakrafli Ismail.

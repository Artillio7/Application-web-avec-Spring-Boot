Nom du Projet : Chatbot Telegram avec Spring Boot
Description

Ce projet est un chatbot Telegram développé en Java avec le framework Spring Boot. Il offre des fonctionnalités comme la consultation de la météo, des blagues aléatoires, et des informations sur les films.
Fonctionnalités

    Météo : Prévisions météorologiques pour une ville donnée.
    Blagues : Fournit des blagues de manière aléatoire.
    Infos Films : Informations détaillées sur les films.

Prérequis

    Java JDK 11+
    Maven
    Compte Telegram et un bot créé via Bot Father

Installation

    Clonez le dépôt :

    bash

git clone [URL du dépôt]
cd [nom du dossier]

Configurez les propriétés dans application.properties :

    Token du bot Telegram
    Clés API pour OpenWeatherMap et autres services utilisés

Construisez et exécutez l'application :

css

    mvn clean install
    java -jar target/[nom-du-fichier].jar

Utilisation

Envoyez des commandes spécifiques au bot pour interagir :

    /weather [ville] pour la météo
    /joke pour une blague
    /movie [titre du film] pour des infos sur un film

Architecture

    Basé sur Spring Boot avec une architecture MVC.
    RestTemplate pour les appels aux API externes.

API et Endpoints

    /weather pour la météo
    /joke pour les blagues
    /movie pour les infos sur les films

Tests

Tests unitaires pour valider la logique des contrôleurs et des services.
Sécurité

    Ne pas exposer les clés API publiquement.
    Utiliser des variables d'environnement pour les tokens.

Contribution

Les contributions sont les bienvenues. Suivez les directives de contribution habituelles.
Licence

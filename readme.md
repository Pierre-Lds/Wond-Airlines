![image1][3]

Wond’Airlines
==========

Elaboration d’une application web de réservation de billets d’avion dans le cadre d’un projet de fin de seconde année de Cycle Informatique et Réseau de l’Institut Supérieur de l’Electronique et du Numérique (ISEN) - Yncréa Ouest.

Warning
------------

Malheureusement, je n'ai plus accès aux base de données et aux scripts python pour populer la bdd.

Prérequis
------------

Afin de pouvoir tester / modifier l’application il faut avoir tous les outils nécessaires.

Pour manipuler la base de données il faut une des installations suivantes :
*    Une plateforme de gestion de base de données compatible MySQL en ligne (telle que phpMyAdmin)
*    MySQL installé sur votre machine et compatible avec votre version de PHP

Les fichiers de codes quant à eux sont lisibles et modifiables sur n’importe quel éditeur de texte ou IDE.


Installation
-------------

Installez la version de PHP 5.6 ou version ultérieure avec la commande suivante :
`php56`
Installez la version de MySQL associée à cette version de PHP avec la commande suivante :
`php56-mysqlnd`    

Avec votre gestionnaire de base de données MySQL ou avec MySQL installé sur votre machine / serveur :

*    Ouvrez le fichier project_db.sql
*    Manipulez les tables comme vous le souhaitez !

Ouvrez les fichiers que vous souhaitez modifier en extensions .php .js .html .sql avec un éditeur de texte ou environnement de développement.

Configuration utilisée
-----------------------
*    Apache 2.4.43 (Amazon)
*    Instance AWS EC2
*    OpenSSL 1.0.2k-fips
*    PHP 5.6.40

Navigation Fichier
---------------------
*    La totalité des fichiers sources sont dans le répertoire du projet
*    Tous les fichiers PHP sont placés dans le répertoire content/ à l'exception d'index.php
*    Tous les fichiers JavaScript sont placés dans le répertoire scripts/
*    Toutes les ressources graphiques sont placées dans le répertoire ressources/
*    Tous les fichiers CSS sont placés dans le répertoire style/

Architecture du site
-------------------------
Ce site est basé sur une architecture MVC allégée (sans Modèle).

![image1][1]

Architecture de la base de données
-----------------------------------------------
Dans votre base de données, vous aurez besoin de différentes tables composées de différents éléments.
Nous avons réalisé un MCD grâce à JMerise pour vous présenter le plus simplement la base de données.

![image1][2]



Légende : Les points rouges représentent les clés étrangères

Développeurs
------------------
La conception de l’application web ont été réalisées par Emeric GUICHET, Pierre LANDAIS, Enzo MOULIN et Antonin SIRET. 

License
------------------
Ce projet est libre de droit et open source.

[1]: https://i.ibb.co/B36DfRc/archisite.png
[2]: https://i.ibb.co/DVdsZtP/mcd.png
[3]: https://i.ibb.co/ck4G75d/logo.png


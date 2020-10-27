# Library

##### Application web développé dans le cadre du projet 7 OpenClassromms du parcours "Développez le nouveay système d'information de la bibliothèque d'une grande ville"
##### Nom du projet "Library d'OC-City"

##### Objet : Création d'un site web pour les bibliothèque d'une grande ville

##### Contexte : 

La DSI est en charge de tous les traitements numériques pour la
mairie et les structures qui lui sont rattachées, comme la gestion
du site web de la ville par exemple. À ce titre, Patricia est
contactée par le service culturel de la ville qui souhaite
moderniser la gestion de ses bibliothèques. John, architecte
logiciel, sera chargé de la validation technique du projet.

## Projet 

##### Fonctionnalités du site web :

* Recherche des ouvrages et voir le nombre d'exemplaires disponibles
* Consulter leurs prêts en cours. Les prêts sont pour une pédiode de 4 semaines
* Prolonger un prêt en cours. Le prêt d'un ouvrage n'est prolongeable qu'une seule fois. La prolongation ajoute une nouvelle période de prêt (4semaines) à la pédiode initiale.

##### Batch :
Le logiciel pour les traitements automatisés permettra d'envoyer des mails de relance aux usagers n'ayant pas rendyu les livres en fin de période de prêt.

##### L'API web 
Le site web et le batch communiqueront avec ce logicel en REST afin d'utilisaer les informations liées à la base de données.

##### Les contraintes fonctionnelles 

* Application web avec un framework MVC
* API web en REST: les clients (site web et batchs) communiqueront avec cette API web
* Packaging avec Maven

##### Développement 

Les outils pour le développement sont :
- IDE : IntelliJ IDEA 
- Java 11
- Tomcat 9
- Spring Boot version t2.3.3
- Thymeleaf 
- Base de données MySQL  8

##### Déploiement Base de données

	- L'application à été configurée pour une base de données MySQL.
	
	- Installer  MySQL Workbench. Téléchargement et documentation sur https://www.mysql.com/fr/products/workbench/.
	
	- Créer un profil utilisateur avec les droits de création et de gestion de base de données. (username='admin' & password='admin')
	
	- Utiliser les scripts SQL dans MySQLWorkbench dans l'ordre ( create_database.sql , create.sql , library_insert_01.sql , library_insert_02.sql , library_insert_03.sql ) pour pouvoir utiliser les données. (Scripts télécharger via le github )

##### Déploiement Application

Les différents composants sont disponibles aux liens suivants : 

	- API : https://github.com/Benoitdu53/api-library
	
	- client web : https://github.com/Benoitdu53/web-library
	
	- Batch : https://github.com/Benoitdu53/batch-library
	
	- Liens principal : https://github.com/Benoitdu53/Library ( Contient les scripts)
	
Pour le déploiement de l'application chaque composant à un ReadMe à suivre.Il est important de d'abord lancé l'api et après soit le client web ou le batch.
Si problème, fermé vos terminal et relancer en suivant l'ordre API, client web et batch.

##### Auteur 

BRICHET Benoît 


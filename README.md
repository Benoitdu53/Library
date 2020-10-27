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
- Spring Boo version t2.3.3
- Thymeleaf 
- Base de données MySQL  8


##### Déploiement

Les différents composants sont disponibles aux liens suivants : 

	- API : https://github.com/Benoitdu53/api-library
	
	- client web : https://github.com/Benoitdu53/web-library
	
	- Batch : https://github.com/Benoitdu53/batch-library
	
	- Liens principal : https://github.com/Benoitdu53/Library ( Contient les jar, ainsi que les scripts)
	

##### Auteur 

BRICHET Benoît 


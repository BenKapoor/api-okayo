# api-okayo

L'application a été développée avec Spring Boot. Celle-ci permet de certaines fonctionnalités liées à la facturation :
- connexion à la plateforme
- lister les factures
- ajouter une facture

Prérequis :
- Installation du serveur de base de données sur la machine (XAMPP ou WAMPP)
- Créer la base de données "okayo".


Lancement de l'application :
- Télécharger le projet
- A partir de la racine du projet executer la commande : mvn spring-boot:run
- A partir d'un navigateur, accéder à : http://localhost:8080/facture/

Swagger :
Lorsque l'application est lancée aller sur : http://localhost:8080/swagger-ui.html#/

Javadoc :
Accéder à la javadoc en suivant le chemin dans votre explorateur de fichier une fois le projet téléchargé: ../api-okayo/doc/index.html

Technologies utilisées :

- Spring Boot
- JpaRepository
- Mysql
- Heroku
- JUnit
- Swagger

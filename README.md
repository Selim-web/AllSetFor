# Systeme d'authentification Symfony 

Lancer les commandes suivante pour essayer le projet 
1. git clone https://github.com/Selim-web/AllSetFor.git 
2. cd AllSetFor
3. composer install 
4. Dans le fichier .env, remplacer db_user et db_password par vos identifiants serveur local mysql et db_name par le nom souhaité 
5. symfony console doctrine:database:create // Creation de la base de donnée db_name
6. symfony console doctrine:database:import AllSetForBase.sql // Importer la base de donnée fourni afin de pouvoir faire l'authentification 
7. symfony serve -d // Afin de lancer le serveur en local 
8. Ouvrir le lien http dans un navigateur 
9. Vous avez un compte, connectez-vous, sinon inscrivez-vous. 

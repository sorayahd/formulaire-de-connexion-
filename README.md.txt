Technologies utilisées: 

Framework symfony.
Bootsrap 5.
Base de données Mysql.

On tombe directement sur la page d'acceuil,on peut choisir de se connecter ou d'ajouter un compte,
quand on clique sur "ajouter un compte" on tombee sur le formulaire de connexion avec le logo et les 3 boutons
 (valider,ajouter un compte,reset) comme demandés dans l'exercice.

Si on essaye de creer un compte avec un identifiants déja existant,une erreure s'affiche.
En cas d'identifiant ou mot de passe eronnés,une erreur s'affiche.
 


Concernant la base de donnés,c'est une base de données MySQL gérée avec phpMyAdmin,
Dans la table user je stock les identifiants qui sont unique ,ainsi que les mot de passes sous 
un systeme de hashage pour des raisons de sécurité.


Pour se connecter :il faut installer php,symfony,composer, et mysql ,ainsi qu'un serveur local appache,pour ma 
part c'était xampp,puis saisir dans le fichier de configuration .env le nom de la base de données 
ainsi que le mot de passe pour pouvoir se connecter à la base de données.

Finalement il reste qu'a lancer le server sur  http://localhost:8000.

la route /login mène au formulaire de connexion.
la route /register mène au formulaire d'inscription.



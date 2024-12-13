# TpSymfony


Voici une application des gestion d'utilisateur et de réservation. J'ai malheureusment eu des problème avec l'authentification, ce qi m'a contraint à tout recommencer, donc il manque la plupart des vérification. Néanmoins, je pospose une interface agréable et efficace en tailwind. Ce projet à été créé à l'aide de composer et de Symfony 7.2.

1. Installation

Tout d'abord, il faut cloner ce repository sur votre ordinateur avec "git clone "lien-du-repository".
Une fois ceci fait, il faut se déplacer dans le dossier et executer la commande "composer install", afin d'installer les dépendances de symfony installées sur le projet.
Par ailleurs n'oubliez pas de changer la configuration du fichier ".env" afin de mettre vos informations de BDD.
Il faudra utiliser la commande "php bin/console doctrine:database:create" pour créer votre database
Enfin, pour tester, il suffit de lancer la commande "symfony serve" et aller sur votre navigateur et aller vers l'URL : "http://localhost:8000". N'oubliez pas de lncer vos serveur MySQL et Apache.

2. Utilisation

Plusieur pages s'offrent à vous, la méthode CRUD fonctionne sur les Users et les Réservations, donc il vous suffit d'aller sur ces URL : "http://localhost:8000/user" ou "http://locahost:8000/reservation" pour vous amusez ;)

Bon courage et bonne gestion 

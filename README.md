# Benjamin_Piette_ASISRC_2022_Docker

Projet docker ASISR-C 2022 à rendre pour le 06 février 2022.

# Nous allons voir les différentes étapes pour bien réaliser ce TP :

1 ère étapes : Nous devons d'abord nous creer un compte Github et après creer un répository. 

2 ème étape : Nous ouvrons maintenant un terminal comme par example CMD, en administrateur de préférence. Nous vérifions par la suite si nous possédons bien le Docker_Compose en introduisant la commade suivante : docker-compose -v

3 ème étape : Ensuite, il faudra se rendre dans le dossier qui contient le fichier Docker-Compose que nous avons chercher juste avant. Pour ma part, il se trouve ici : cd C:\Users\Users\Documents\Benjamin_Piette_asisrc_2022_docker
Il ne manquera plus que d'utiliser la commande suivante pour lancer le conteneur : docker-compose up

4 ème étape : Stopper le docker-compose up que nous venons d'éxécuter avec un CTRL+C

5 ème étape : Nous pouvons lancer en arrière-plan le docker-compose si nous possédons plusieurs conteneurs exécutables. Il faudra utiliser cette commande : docker-compose up -d.

6 ème étape : Une fois le conteneur éxécuté sans problème, nous pouvons nous rendre sur http://localhost:3000 pour voir si tout fonctionne correctement.

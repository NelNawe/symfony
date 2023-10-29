# symfony
**PROJET SYMFONY AVEC DOCKER**

**Description**
Ce projet consiste à créer un projet crud symfony avec docker.
Faire le projet avec un environnement de de dev et un environnement de production.

**Prérequis**

 * PHP 
 * Symfony CLI
 * MySQL
 * Docker 
 * Un editeur de code(dans ce cas nous utilisons vscode)
 * Une distribution linux pour les utilisateurs de windows (dans ce cas nous utilisons WLS2 avec Ubuntu)

**Installation**

 * Installer et configurer PHP avec Symfony
 * Ouvrir un invite de commande
 * Cloner le dépot 
    git clone https://github.com/NelNawe/symphony
 * Se mettre sur le repertoire du projet 
    cd symphony
 * Creer un fichier .env pour stocker les variables d'environnement
 * Construire et lancer le conteneur docker 
   docker-compose up -d

**Utilisation**

 * Lancer le projet 
   docker exec www_docker_symfony composer create symfony/website-skeleton project

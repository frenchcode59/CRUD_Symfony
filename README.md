# CRUD_Symfony# CRUD Symfony

[![Symfony](https://img.shields.io/badge/Symfony-5.3-000000?logo=symfony)](https://symfony.com/)
[![PHP](https://img.shields.io/badge/PHP-7.4-777BB4?logo=php)](https://www.php.net/)
[![License](https://img.shields.io/github/license/frenchcode59/CRUD_Symfony)](https://github.com/frenchcode59/CRUD_Symfony/blob/main/LICENSE)

Un exemple de projet Symfony pour la création, la lecture, la mise à jour et la suppression (CRUD) d'acteurs , de films et de genre.

## Fonctionnalités

- Affichage de la liste des acteurs
- Création d'un nouvel acteur
- Modification d'un acteur existant
- Suppression d'un acteur
  
- Affichage de la liste des films
- Création d'un nouvel films
- Modification d'un film existant
- Suppression d'un film

-  Affichage de la liste des film par genre

## Prérequis

- PHP 7.4 ou version ultérieure
- Composer - [Téléchargement](https://getcomposer.org/download/)
- Symfony CLI - [Installation](https://symfony.com/download)

## Installation

1. Clonez ce référentiel :

```shell
git clone https://github.com/frenchcode59/CRUD_Symfony.git

Accédez au répertoire du projet :
shell
Copy code
cd CRUD_Symfony
Installez les dépendances avec Composer :
shell
Copy code
composer install
Configurez la base de données dans le fichier .env :
dotenv
Copy code
DATABASE_URL=sqlite:///%kernel.project_dir%/var/data.db
Créez la base de données et effectuez les migrations :
shell
Copy code
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
Démarrez le serveur de développement :
shell
Copy code
symfony serve
Accédez à l'application dans votre navigateur à l'URL http://localhost:8000.
Contribuer
Les contributions sont les bienvenues ! Si vous souhaitez améliorer ce projet, veuillez suivre les étapes suivantes :

Forkz ce référentiel
Créez votre branche de fonctionnalité (git checkout -b ma-nouvelle-fonctionnalite)
Effectuez les modifications nécessaires et ajoutez-les (git add .)
Commitz vos modifications (git commit -m 'Ajouter une nouvelle fonctionnalité')
Pushez votre branche (git push origin ma-nouvelle-fonctionnalite)
Ouvrez une demande d'extraction dans ce référentiel

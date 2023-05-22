##

- Acceuil

- Liste des livres
- Création d'un livre *
- Details d'un livre
- Modification d'un livre *
- Suppression d'un livre *

- Création d'un compte utilisateur (register)
- Connexion
- Déconnexion

- Mon profil *


* Pages sécurisés


## Routes (path)

- /

- /books                INDEX
- /book                 CREATE
- /book/{id}            READ
- /book/{id}/edit       UPDATE
- /book/{id}/delete     DELETE

- /authors              INDEX
- /author               CREATE
- /author/{id}          READ
- /author/{id}/edit     UPDATE
- /author/{id}/delete   DELETE

- /register             Création du compte utilisateur
- /login                Connexion
- /logout               Déconnexion

- /profile
- /profile/edit
- /profile/delete


## Controllers

- HomeController::index() 

- BookController::index()
- BookController::create()
- BookController::read()
- BookController::update()
- BookController::delete()

- AuthorController::index()
- AuthorController::create()
- AuthorController::read()
- AuthorController::update()
- AuthorController::delete()

- RegisterController::index() **

- SecurityController::login() **
- SecurityController::logout() **

- ProfileController::index()
- ProfileController::update()
- ProfileController::delete()

** Controllers générés par Symfony


## Entités

- Book                  php bin/console make:entity Book
- Author                php bin/console make:entity Author
- User                  php bin/console make:xxxxxxxxxxxxxx
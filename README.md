# Application de gestion de membres

Cette application web est en deux parties : une partie backend et une partie frontend.

## Installation

### Le backend
Le backend est constitué d'un serveur API connecté à une base de données MySQL. Pour les besoins de cette application web, il est nécessaire d'installer un serveur web et un serveur de base de données. J'ai utilisé la suite logicielle `XAMPP`. Une fois XAMPP installé, il faut importer la base de données appelée `nodejs` contenant une table appelée `members`. Le fichier `nodejs.sql` permet de faire cette importation et se trouve dans le dossier `Backend`.

Puis se rendre dans le dossier `Backend` via un terminal et taper `npm install`. Ensuite, taper `npm start`. Le serveur va démarrer à l'adresse `http://localhost:8080`.


### La documentation de l'API
Pour voir la documentation de l'API au format Swagger, ouvrir le navigateur et taper l'adresse `http://localhost:8080/api/v1/api-docs`.
Il existe également une documentation de cette API à l'adresse `https://charlenry.gitbook.io/api-rest-for-member-management/`.


### Le frontend
Se rendre dans le dossier `Frontend` via un autre terminal et taper `npm install`. Puis taper `npm start`. Par la suite, ouvrir le navigateur et saisir l'adresse `http://localhost:8081`.


### Utilisation de l'application web
Une fois que vous êtes à l'adresse `http://localhost:8081`, vous avez accès à la liste des membres, chacun ayant un ID et un nom. Vous pouvez cliquer sur un membre pour voir ses informations en particulier. Vous avez un bouton `Modifier` pour modifier le nom du membre. Dans la page de modification, vous pouvez également supprimer le membre. Enfin dans la liste des membres, vous pouvez aussi ajouter un nouveau membre.



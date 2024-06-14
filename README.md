# Plateforme Web de comptabilité

Une plateforme en ligne de gestion comptable qui offre aux utilisateurs la possibilité de gérer les
clients, les fournisseurs, les factures, les opérations bancaires et les opérations de caisse.

## Prérequis

- [Node.js](https://nodejs.org/) (version 14 ou plus récente)
- [Angular CLI](https://angular.io/cli) (version 12 ou plus récente)
- [Composer](https://getcomposer.org/) (version 2 ou plus récente)
- [PHP](https://www.php.net/) (version 7.4 ou plus récente)
- [Symfony CLI](https://symfony.com/download) (facultatif, mais recommandé)

## Installation

### Backend (Symfony)

1. Clonez le dépôt du projet :

    ```bash
    git clone https://github.com/votre-utilisateur/votre-projet.git
    cd votre-projet/backend
    ```

2. Installez les dépendances avec Composer :

    ```bash
    composer install
    ```

3. Configurez votre base de données dans le fichier `.env` :

    ```ini
    DATABASE_URL="mysql://db_user:db_password@127.0.0.1:3306/db_name"
    ```

4. Créez la base de données et les tables :

    ```bash
    php bin/console doctrine:database:create
    php bin/console doctrine:migrations:migrate
    ```

5. Démarrez le serveur Symfony :

    ```bash
    symfony server:start
    ```

### Frontend (Angular)

1. Accédez au répertoire frontend :

    ```bash
    cd ../frontend
    ```

2. Installez les dépendances avec npm :

    ```bash
    npm install
    ```

3. Démarrez l'application Angular :

    ```bash
    ng serve
    ```

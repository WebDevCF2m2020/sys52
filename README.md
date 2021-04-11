## sys52
Exemple d'installation de Symfony en 5.2.6 (version au moment de l'installation) en version --full (la plupart des bundles principaux sont déjà installés)
### Requis en local
- PHP 7.2 minimum
- MySQL ou MariaDB
- composer : https://getcomposer.org/download/
- symfony : https://symfony.com/download
### Installation de Symfony
    symfony new --full sys52

    // entrée dans le dossier
    cd ./sys52

    // lancement du serveur en mode daemon
    symfony server:start -d
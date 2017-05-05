# Hello World

## Utilisation de codecov et Travis : TP d'études


1. Installations

    ```
    $ npm install [-g] mocha
    $ npm install [-g] chai
    $ npm install [-g] codecov
    $ npm install [-g] istanbul
    ```

2. Configuration de Travis (facilite l'utilisation de Codecov)

    Création d'un fichier nommé .travis.yml avec la configuration pour faire fonctionner les différents modules.


3. Run de istanbul

    Lancer la commande suivante pour lancer les tests de couverture :
    ```
    $ istanbul cover ./node_modules/mocha/bin/_mocha -- -R spec --recursive
    ```


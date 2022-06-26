# PHPUnit

Bonjour, ceci est le cours de test unitaire avec  PHPUnit, durant la session de Formation DWWM 2022.

Cloner ce repo sur votre machine :

```GIT
git clone https://github.com/mikaeltrilles/PHPUnit.git
````
ou créer un projet vide et initialisez le avec composer :

```BASH
composer init
```

Validez les questions posées par composer, ensuite à la définition des dépendences suivez ces reponses :

```BASH
Define your dependencies.

Would you like to define your dependencies (require) interactively [yes]? no
Would you like to define your dev dependencies (require-dev) interactively [yes]? yes
Search for a package: phpunit
Info from https://repo.packagist.org: #StandWithUkraine

Found 15 packages matching phpunit

   [0] phpunit/phpunit 
   [1] phpunit/php-timer 
   [2] phpunit/php-text-template 
   [3] phpunit/php-file-iterator 
   [4] phpunit/php-code-coverage 
   [5] phpunit/phpunit-mock-objects Abandoned. No replacement was suggested.
   [6] symfony/phpunit-bridge 
   [7] phpunit/php-invoker 
   [8] phpunit/php-token-stream Abandoned. No replacement was suggested.
   [9] johnkary/phpunit-speedtrap 
  [10] phpstan/phpstan-phpunit 
  [11] jean85/pretty-package-versions 
  [12] brianium/paratest 
  [13] yoast/phpunit-polyfills 
  [14] spatie/phpunit-snapshot-assertions 

Enter package  : 0
```

## Rendez vous sur [Packagist](https://packagist.org/packages/phpunit/phpunit) à la page de PHPUnit.

Recupérons les dernières versions de PHPUnit depuis Packagist.

```PHP
composer require phpunit/phpunit
```
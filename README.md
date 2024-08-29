firstSymfony 

installation : 

symfony new firstSymfony

nous voici avec un symfony vierge 


## lancement de symfony

on change de repertoire

´´´bash 
cd firstSymfony 

##pour lancer le serveur 
symfony serve
# ou 
symfony server :start
#ou
symfony serve -d pour mettre en mode deaMon (symfony.exe execute en arrier plan sous windows)
#ou 
php -S localhost:8000 -t public symfony server:start

https://127.0.0.1:8000

###installer de maker budle
documentation : https://symfony.com/doc/current/bundles/MakerBundle/index.html

composer require --dev symfony/maker-bundle
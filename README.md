# docker-laravel
This is structure to help us to create an environment in order to use in any version of PHP


You need CHANGE THE VERSION OF PHP according your laravel version, this chage you should in the file Dockerfile
Especificly inb the next line
FROM php:7.3-fpm-alpine


Going to the folder src in command line, In  the folder src you going to install the last version of laravel with the next command:
laravel

Last version laravel
composer create-project laravel/laravel .

Especific version laravel
composer create-project laravel/laravel . 5.7
# docker-LEMP-template

Docker yml file and Dockerfiles for develop LEMP.

# develop enviloment
php:8.1-fpm

nginx:latest

mysql:8.0


# Usage
1. copy .env.example and rename to .env
2. write passwords in .env
3. run below command 

   docker compose build
   
   docker compose up -d

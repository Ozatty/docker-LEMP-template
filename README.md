# docker-LEMP-template

Docker yml file and Dockerfiles for develop LEMP.

# develop enviloment
<dl>
  <dt>php:8.1-fpm</dt>
  <dt>nginx:latest</dt>
  <dt>mysql:8.0</dt>
</dl>

# Usage
1. copy .env.example and rename to .env
2. write passwords in .env
3. run below command 
   docker compose build
   docker compose up -d

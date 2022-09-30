# docker-LEMP-template
nginx + php8.1-fpm + mysql 8.0 in docker container. 


# develop enviloment
- php:8.1-fpm  
- nginx:latest  
- mysql:8.0  


# Usage
1. git clone this code url
~~~
git clone git@github.com:Ozatty/docker-LEMP-template.git
~~~
2. copy .env.example and rename to .env
~~~
cp .env.example .env
~~~
3. write each password in .env
4. make src directory
~~~
   mkdir src
~~~
5. run below command  
~~~
   docker compose build  
   docker compose up -d  
~~~

#  LAMP stack built with Docker Compose

* PHP
* Apache
* MySQL
* phpMyAdmin
* Redis

As of now, we have several different PHP versions. Use appropriate php version as needed:

* 5.4.x
* 5.6.x
* 7.1.x
* 7.2.x
* 7.3.x
* 7.4.x


##  Installation
 
* Clone this repository on your local computer
* configure .env as needed 
* Run the `docker-compose up -d`.

```shell

cd docker-compose-lamp/
cp sample.env .env
// modify sample.env as needed
docker-compose up -d
// visit localhost
```
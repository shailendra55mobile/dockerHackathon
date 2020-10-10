# PHP

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)

<img align='right' src="https://miro.medium.com/max/624/1*hWVuG63ZyXU7o8idgUHW5g.gif">

### 1) Create a sample project with database connection and check database connetion is successfull or not.
### 2) Create a Dockerfile to serve the project using apache/nginx web server.
### 3) Create a docker-compose to setup the local environment.

## Note:
* Container name must be php-con.
* Image name must be php-img.
* Make sure you choose base linux image like ubuntu,centos,mariadb,php,composer,nginx etc.
* Please do not use third party images for serve the project.
* You can use multistage dockerfile for serve the project.
* The build layers of the images must be less.
* Make sure to choose compose file version 3.
* The network must be defined under docker-compose. 


## Best Practices for Dockerfile and docker-compose.
* Use volume in docker-compose for runtime changes.
* Include comments on every step in Dockerfile and docker-compose file.
* Please include maintainer in Dockerfile.


<img align='center' src="https://www.developersacademy.org/blog/wp-content/uploads/2018/04/php-1024x538.png">

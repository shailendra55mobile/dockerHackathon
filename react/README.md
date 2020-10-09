# React application

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)

<img align='right' src="https://miro.medium.com/max/624/1*hWVuG63ZyXU7o8idgUHW5g.gif">

### 1) Create a sample project for react application with one test case.
### 2) Make sure use nodejs base image with version.
### 3) Create a Dockerfile to serve the project using apache/nginx web server.
### 4) Create docker-compose to setup the local environment.

## Note:
* Container name must be react-con.
* Image name must be react-img.
* Make sure you choose base linux image like ubuntu,centos,nginx,apache,nodejs etc.
* Please do not use third party images for serve the project.
* You can use multistage dockerfile for serve the project.
* The build layers of the images must be less.


## Best Practices for Dockerfile and docker-compose.
* Use volume in docker-compose for runtime changes.
* Include comments on every step in Dockerfile and docker-compose file.
* Please include maintainer in Dockerfile.

<img align='center' src="https://miro.medium.com/max/3600/1*HSisLuifMO6KbLfPOKtLow.jpeg">
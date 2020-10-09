
# Dotnet application

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)

<img align='right' src="https://miro.medium.com/max/624/1*hWVuG63ZyXU7o8idgUHW5g.gif">

### 1) Create a sample project for dotnet application.
### 2) Install all dependencies on core images for the project in Dockerfile.
### 3) Create docker-compose for local setup.

## Note:
* Container name must be dotnet-con.
* Image name must be dotnet-img.
* Make sure you choose base linux image like ubuntu,centos,nginx etc.
* Please do not use third party images for serve the project.
* You can use multistage dockerfile for serve the project.
* The build layers of the images must be less.


## Best Practices for Dockerfile and docker-compose.
* Use volume in docker-compose for runtime changes.
* Include comments on every step in Dockerfile and docker-compose file.
* Please include maintainer in Dockerfile.

<img align='center' src="https://fwdsgf.com/wp-content/uploads/2018/01/logo-dot-net-framework.png">
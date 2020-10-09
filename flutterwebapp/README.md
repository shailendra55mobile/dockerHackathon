# Flutter web app

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-for-android.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)
<img align='right' src="https://miro.medium.com/max/624/1*hWVuG63ZyXU7o8idgUHW5g.gif">

### 1) Create a sample project for flutter web app
### 2) Create a docker file for install all dependencies and serve the project using apache/nginx.
### 3) Create a docker-compose to setup the local environment.

 
## Note:
* Container name must be flutter-con.
* Image name must be flutter-img.
* Make sure you choose base linux images like ubuntu,centos,nginx,apache etc.
* Please do not use third party images to serve the project.
* You can use multistage Dockerfile to serve the project.
* The build layers of the images must be less.


## Best Practices for Dockerfile and docker-compose.
* Use volume in docker-compose for runtime changes.
* Include comments on every step in Dockerfile and docker-compose file.
* Please include maintainer in Dockerfile.

<img align='center' src="https://dashbouquet.com/static/020b2d58fcc9ac999513a862aa01314c/d47f1/flutter-app-development-post.jpg">


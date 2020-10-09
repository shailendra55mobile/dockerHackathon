# How to setup Docker in your os ?
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-responsibility.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)

<img align='right' src="https://miro.medium.com/max/624/1*hWVuG63ZyXU7o8idgUHW5g.gif">

### Creating Dockerfile 🐋🐋🐋
Docker can build images automatically by reading the instructions from a Dockerfile. A Dockerfile is a text document that contains all the commands a user could call on the command line to assemble an image.<br />
To learn more we can check official docs [here](https://docs.docker.com/engine/reference/builder/)

### About docker compose 🐋🐋🐋
Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration. 
<br />
To learn more we can check official docs [here](https://docs.docker.com/compose/)

### To setup docker in your [Windows](https://docs.docker.com/docker-for-windows/install/) 🐋🐋🐋

* To download the docker hub click [here](https://hub.docker.com/editions/community/docker-ce-desktop-windows/).
* Install the application.
* Start Docker Desktop.
<br />

![Test Image](https://docs.docker.com/docker-for-windows/images/docker-app-search.png)
<br />

* When the whale icon in the status bar stays steady, Docker Desktop is up-and-running, and is accessible from any terminal window.
<br />

![docker icon](https://docs.docker.com/docker-for-windows/images/whale-icon-systray.png)

* When the initialization is complete, Docker Desktop launches the onboarding tutorial. The tutorial includes a simple exercise to build an example Docker image, run it as a container, push and save the image to Docker Hub.
<br />

![docker tutorial](https://docs.docker.com/docker-for-windows/images/docker-tutorial-win.png)

### To setup docker in you [Mac Os](https://docs.docker.com/docker-for-mac/install/) 🐋🐋🐋

* To download the docker hub click [here](https://hub.docker.com/editions/community/docker-ce-desktop-mac/)
* Install and run Docker Desktop on Mac
* Double-click Docker.dmg to open the installer, then drag the Docker icon to the Applications folder.
<br />

![docker mac icon](https://docs.docker.com/docker-for-mac/images/docker-app-drag.png)

* Double-click Docker.app in the Applications folder to start Docker. (In the example below, the Applications folder is in “grid” view mode.)
<br />

![docker mac icon](https://docs.docker.com/docker-for-mac/images/docker-app-in-apps.png)
<br />

![docker mac icon](https://docs.docker.com/docker-for-mac/images/whale-in-menu-bar.png)

* If you’ve just installed the app, Docker Desktop launches the onboarding tutorial. The tutorial includes a simple exercise to build an example Docker image, run it as a container, push and save the image to Docker Hub.
<br />

![docker mac icon](https://docs.docker.com/docker-for-mac/images/docker-tutorial-mac.png)

* Click the Docker menu (whale menu) to see Preferences and other options.

* Select About Docker to verify that you have the latest version.

### To setup docker in your [Linux OS](https://docs.docker.com/engine/install/debian/) 🐋🐋🐋

* Attached the essential commands to install docker and docker-compose

```bash
sudo apt-get install docker
sudo apt-get install docker-compose
```
* Successfully installed docker
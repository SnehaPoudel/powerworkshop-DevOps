# php-hello-world
A simple hello-world for composer

Installation using Dockerfile
------------

Build Docker Image
``` bash
docker build -t workshop .
```

Run Docker Image
``` bash
docker run -dp 0.0.0.0:8080:3000 workshop
```

Installation using docker-compose.yml
------------

Build and run Docker Image
``` bash
docker-compose up -d
```

Access the Application
------------

Access the application using <ip-address>:8080

![Site Demo](https://github.com/SnehaPoudel/powerworkshop-DevOps/blob/main/ss.PNG?raw=true)

Configure GitHub Actions
------------

![GitHub Actions](https://github.com/SnehaPoudel/powerworkshop-DevOps/blob/main/ss1.PNG?raw=true)

Pushing Image to DockerHub
------------

Build Docker Image
``` bash
docker build -t your_username/devops-workshop:latest .
```

Login to DockerHub
``` bash
docker login
```

Push the Docker Image
``` bash
docker push your_username/devops-workshop:latest
```

![DockerHub](https://github.com/SnehaPoudel/powerworkshop-DevOps/blob/main/ss2.PNG?raw=true)


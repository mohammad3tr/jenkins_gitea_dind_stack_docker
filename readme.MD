1- detup your mirrir repository
2- see https://github.com/mohammad3tr/Docker-Registery.git

3- vim Dockerfile-dind and set your mirror repoistory address that setup in step1

  
4- docker build -t m3tr-dind -f Dockerfile-dind . //build your dind image

5- docker build -t m3tr-jenkins -f Dockerfile-jenkins . //build your Jenkins image

5-docker-compose up -d

6- http://<your url>:8080 //Jenkins UI

7- http://<your url>:3000 //Gitea UI

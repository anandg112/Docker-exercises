# Docker-exercises
Creating Dockerfile and docker-compose for various projects (Node app, Drupal etc.)

## Key Docker Commands
```docker container run --publish 80:80 nginx``` --> Downloaded image 'nginx' from Docker hub, Started a new container from that image, Opened port 80 on the host IP, Routes that traffic to the container IP, port 80 <br />
```docker container run --publish 80:80 --detach nginx```--> Tells docker to run the container in background  <br />
```docker container rm -f containerName``` --> To remove a container by forcing <br />
```docker container top``` - process list in one container <br />
```docker container inspect``` - details of one container config <br />
```docker container stats``` - performance stats for all containers <br />
```docker container start``` -ai containerName - To restart a container <br />
```docker container run -it```  - start new container interactively <br />
```docker container exec -it``` - run additional command inside existing container <br />
```docker-compose up``` - setup volumes/networks and start all containers <br />
```docker-compose down``` - stop all containers and remove cont/vol/net <br />

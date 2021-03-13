| Command name       | Syntax     | Explanation    | Example  |
| :------------- | :----------: | :-----------: | :---------:   |
|  Info | docker info   | Get Docker System information | docker info |
|  Images  | docker images | Get all images on the local machine | docker images |
|  Run  | docker run IMAGE [COMMAND] | Create container from a given image(image is specified as "repository:tag") and run it  | docker run busybox:1.33 echo "hello world" |
|  Run in background with port mapping  | docker run -d -p IMAGE_PORT:HOST_PORT IMAGE | Run the specified image as detached(in background) and map specified image port to specified system port  | docker run -d -p 5000:5000 03b3e73a4303 |
|  Pull  | docker pull IMAGE | Pull an image(image is specified as "repository:tag") hosted on docker hub | docker pull eclipse-mosquitto:2.0.9 |
|  PS  | docker ps | List docker containers which are in running state | docker ps |
|  PS -a  | docker ps -a | List ALL docker containers regardless of state | docker ps -a |
|  Inspect  | docker inspect [CONTAINER ID] | List complete information of a specific container | docker inspect 6f200c88b084ac62757ca4b5fad7f9f05925202cade9e00d25bdbf8a637f4e1f |
|  Stop  | docker stop [CONTAINER ID] | Stop a running container | docker stop 6f200c88b084ac62757ca4b5fad7f9f05925202cade9e00d25bdbf8a637f4e1f |
|  History  | docker history IMAGE | List intermediate image history for a specific image(specified as "repository:tag") | docker history tomcat:8.0 |
|  Build  | docker build docker build [OPTIONS] PATH | Buld an image from a Dockerfile |  docker build -t imgName:sometag . |

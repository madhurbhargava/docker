| Command name       | Syntax     | Explanation    | Example  |
| :------------- | :----------: | :-----------: | :---------:   |
|  Info | docker info   | Get Docker System information | docker info |
|  Images  | docker images | Get all images on the local machine | docker images |
|  Run  | docker run IMAGE [COMMAND] | Create container from a given image(image is specified as "repository:tag") and run it  | docker run busybox:1.33 echo "hello world" |
|  Pull  | docker pull IMAGE | Pull an image(image is specified as "repository:tag") hosted on docker hub | docker pull eclipse-mosquitto:2.0.9 |
|  PS  | docker ps | List docker containers which are in running state | docker ps |
|  PS -a  | docker -a | List ALL docker containers regardless of state | docker ps -a |

| Command name       | Syntax     | Explanation    | Example  |
| :------------- | :----------: | :-----------: | :---------:   |
|  Info | docker info   | Get Docker System information | docker info |
|    | docker images | Get all images on the local machine | docker images |
|    | docker run IMAGE [COMMAND] | Create container from a given image(image is specified as "repository:tag") and run it  | docker run busybox:1.33 echo "hello world" |
|  *Pull*  | docker pull IMAGE | Pull an image(image is specified as "repository:tag") hosted on docker hub | docker pull eclipse-mosquitto:2.0.9 |
# RegUI

RegUI is a basic Graphical User Interface for private docker registries.

### Running the Docker container
```sh
sudo docker build -t nginx docker/
sudo docker run -ti -p 80:80 -v /path/to/code:/usr/share/nginx/html nginx
```
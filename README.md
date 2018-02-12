# PYTHON + DOCKER

A Python 3.6 Flask app that displays random cat pix

### REQUIREMENTS
* Docker

### Installation
```
  > docker run -p 8888:5000 --name myfirstapp fibanez/myfirstapp
```

Head over to http://localhost:8888 and your app should be live. Note If you are using Docker Machine, you may need to open up another terminal and determine the container ip address using docker-machine ip default.

### References 
[2.0 Webapps with Docker](https://github.com/docker/labs/blob/master/beginner/chapters/webapps.md) by PoppyBagel
# README #

To create a docker image, you need to follow the further instructions

* Start a command line shell
* Select the directory where the Dockerfile is located, in my case it is "flaskexapp_dockerfile"
* RUN "docker build --no-cache -t CONTAINER_NAME .", where CONTAINER_NAME is name of Docker container
* RUN "docker run -d -p 5000:5000 CONTAINER_NAME"
* That's all, your docker container is running and you can open project in your browser at: [localhost:5000](http://localhost:5000)

# How-To do a quickstart of Jenkins Docker container

We are going to use here Jenkins Docker official image

## Run the docker container

`docker run --name jen-qs -d -p 8080:8080 jenkins/jenkins:lts`{{execute}}

## Watch docker logs

`docker logs jen-qs`{{execute}}
Wait till Jenkins starts up ("Jenkins is fully up and running" message in the log)

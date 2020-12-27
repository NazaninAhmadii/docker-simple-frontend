# react-docker
Simple React with docker

# How to setup Dockerfile
Dockerfile is the blue print for container, it creates image from our container

To make the image based on the instruction in Dockerfile, run this command: 
```bash
docker build -t frontend .
```

To see your docker images run this command: 
```bash
docker images
```

To delete the docker image run this:
```bash
docker rmi image_id
```

To run docker: 
```bash
docker run -p 3000:3000 frontend
```

Now if you check [localhost:3000](http://localhost:3000/) you will see the react application.

Useful docker command:

To pull image from docker hub
```bash
docker pull image_name
```

To push image to the docker hub
```bash
docker push image_name
```
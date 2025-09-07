## What is Docker Hub Registry

Docker Hub is a cloud-based container registry that connects to your code repos to build, test, store, and distribute images, integrates with Docker Cloud for deployment, and centralizes discovery, change management, collaboration, and workflow automation across the development pipeline.


reference : https://docs.docker.com/get-started/docker-concepts/the-basics/what-is-a-registry/
##### Ref URL : https://docs.docker.com/docker-hub/

1. Create a docker hub account in https://hub.docker.com/

1. Pull a docker image 

   ```sh 
   docker pull ubuntu
   ```

1. pull a docker image with the old version

   ```sh
   docker pull ubuntu:24.04
   ```

1. create a custom tag to the docker image
   ```sh
   docker tag ubuntu:latest valaxy/ubuntu:demo
   ```

1. login to your docker hub registry 
   ```sh
   docker login
   docker push valaxy/ubuntu:demo
   ```

### testing 

1. Remove all images in docker server 
   ```sh 
   docker image rm -f <Image_id>
   ```

1. Pull your custom image from your docker account
   ```sh
   docker pull valaxy/ubuntu:demo
   ```


1. Create a docker hub account in https://hub.docker.com/

1. Pull a docker image

   ```sh
   docker pull ubuntu
   ```

1. pull a docker image with the old version

   ```sh
   docker pull ubuntu:16.04
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


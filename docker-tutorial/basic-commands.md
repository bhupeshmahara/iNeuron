### Here are some basic docker commands:

1. **docker login** : login to your docker account

   ![docker login](https://user-images.githubusercontent.com/70663493/196435822-b3ed6ec4-d7f4-4607-91cb-0e8f75523021.PNG)

2. **docker --version** : tells the docker version

   ![docker version](https://user-images.githubusercontent.com/70663493/196436162-2aba5352-b3ad-448b-a2e6-9161dd6a6f9f.PNG)

3. **docker pull "repository-name"/"image-name"** : pull any image from a repository

   ![docker pull](https://user-images.githubusercontent.com/70663493/196436258-38c52ea6-90ad-492f-a0a1-5d64847192ae.PNG)

4. **docker images** : shows the details of pulled image

   ![docker images](https://user-images.githubusercontent.com/70663493/196436343-21ba3098-1b73-420d-86a5-5a55460f2dca.PNG)

5. **docker run -d -p 80:80 "repository-name"/"image-name"** : it runs the docker image
   - **-d** : run the container in detached mode (in background)
   - **-p 80:80** : map port 80 of the host to port 80 of the container

   ![docker run](https://user-images.githubusercontent.com/70663493/196438093-032907f4-dd8a-4c7f-a930-54e29f882e79.PNG)

6. **docker ps** : shows the details of running containers
  
   ![docker ps](https://user-images.githubusercontent.com/70663493/196438205-5fecb1ca-99ef-4238-8736-b37648a5db9c.PNG)

7. **docker build -t "image-name" .** : build a docker image from scratch
  
   ![docker build](https://user-images.githubusercontent.com/70663493/196438310-c604261a-e7e8-480e-88d3-c8333058047b.PNG)
   ![docker build 1](https://user-images.githubusercontent.com/70663493/196438368-a582a2a5-8c50-46a2-aca4-583cfedd7c27.PNG)

   check for newly build image
  
   ![docker images new](https://user-images.githubusercontent.com/70663493/196439058-f4455ee5-aa49-4d55-a7cf-858083e49e3a.PNG)

   start the newly build docker image
  
   ![docker run new](https://user-images.githubusercontent.com/70663493/196439151-ef93c2e3-488b-4db9-84f0-98966c6e18aa.PNG)

8. **docker stop <container-id>** : stops the docker
  
   ![docker stop](https://user-images.githubusercontent.com/70663493/196439417-62b6c0cf-caca-4997-be39-0230ed227e5f.PNG)

9. **docker push <repository-name>/<image-name>** : push the docker container to docker hub
  
   ![docker push](https://user-images.githubusercontent.com/70663493/196439469-fdeae918-de94-47bb-9d02-725aec8ae00a.PNG)
   ![docker container](https://user-images.githubusercontent.com/70663493/196439539-a1929eae-0b7a-4962-a19c-3772a1e01be5.PNG)

10. **docker rmi -f "repository-name"/"image-name"** : removes the docker repository and image name
  
    ![docker rmi](https://user-images.githubusercontent.com/70663493/196439634-29e37925-cf91-4e61-a53e-9b17c2df7e15.PNG)

11. **docker logout** : logout from docker environment
   
    ![docker logout](https://user-images.githubusercontent.com/70663493/196439730-337c6a94-3227-4511-a2e8-25346043a06c.PNG)

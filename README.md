# Demo_SpringBoot_AwsEcsFargateDeployment

Demo deployment of a Spring Boot Application on Amazon Web Services (AWS) Elastic Container Service (ECS) and Fargate

1. Spring Boot Application's Docker Image was built using: mvn spring-boot:build-image.
2. Docker image was uploaded from local PC to Docker Hub.
3. On AWS, a new ECS task definition was created. Docker Hub Image details added in the Container.
4. An ECS cluster was created, and the above task definition was added to the cluster. Fargate launch type was used for this example.

<br/>
AWS Console screenshot: <br/>
<img width="960" alt="image" src="https://user-images.githubusercontent.com/96373227/186231689-cc6dd886-ffbe-4f56-b4e6-d85c0a9b2209.png">

Application running screenshot:<br/><br/><br/>
<img width="960" alt="image" src="https://user-images.githubusercontent.com/96373227/186231456-e76c89d8-e92a-43a0-a079-737323516bbc.png">

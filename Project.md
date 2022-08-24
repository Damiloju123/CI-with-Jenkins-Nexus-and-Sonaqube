Step 1: Log on to AWS console and spin up 3 Instances 

Step 2: Set up the following 
Jenkins - Ubuntu
Nexus - Centos
Sonarqube - Ubuntu
Security Groups

Step 3: Log in to verify each of the services 

Step 4: Install plugins to be used in Jenkins

![plugins](https://user-images.githubusercontent.com/52894481/186391032-6b158284-42f8-463c-876c-77d03a1f87ad.JPG)

Step 5: Intergrate Sonar Cube with Jenkins 
- Download Sonarcube Scanner via Global Tool COnfiguration on Jenkins
![sonarcube scanner](https://user-images.githubusercontent.com/52894481/186392002-dea85176-e158-44b8-89c8-9324450d5409.JPG)

- Configure it using token created via Sonarqube
![sonarcube config](https://user-images.githubusercontent.com/52894481/186392385-2303779f-ab22-48bc-89fd-1a74f9097f3e.JPG)

Step 6: Create a Jenkins file which involves Code Anaysis with Sonar Cube 

- Code Analysis  helps detect vulnerability and functional errors 
![image](https://user-images.githubusercontent.com/52894481/186392685-898e570b-ea6f-4d61-853f-111ca51ed8db.png)

Step 7: Create & Build a Jenkins Pipeline

![paac_sonar](https://user-images.githubusercontent.com/52894481/186392828-4b16a6f7-de8b-47f8-8d9c-cdba8f31f58b.JPG)

Step 8: View Code test status with Sonarqube.

![sonarcube out](https://user-images.githubusercontent.com/52894481/186393270-f42f302d-563d-4e84-b378-1f9d4ca6c108.JPG)
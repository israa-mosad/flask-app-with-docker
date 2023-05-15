# flask-app-with-docker
This is just a simple example of a DevOps project related to Docker. There are many other things you could do with Docker, such as creating a CI/CD pipeline for your application or deploying your application to a cloud platform

Steps:-
--
1- Create a simple web application in your favorite programming language.
 
2- Create a Dockerfile for your application.

3- Build your Docker image

   ##### $ docker build -t my-app .

4- Push your Docker image to a Docker registry :- 
  ##### $ docker push my-app


5- Create a Kubernetes deployment for your application.

6- Deploy your application to Kubernetes :- 
##### $ kubectl apply -f deployment.yaml

#### Once the application is deployed, you can access it at http://localhost:8080.





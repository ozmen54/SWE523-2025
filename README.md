# SWE 523 ADVANCED DISTRIBUTED INFORMATION AND MANAGEMENT

Please click the link below to see the projects: <br>
[SWE523 Project Descriptions](SWE523_ProjectDescriptions_2025.pdf) <br>
Each person must select one unique project.  

## Projects:

<table>
  <header>
    <th>No</th>
    <th>Project Title</th>
    <th>Tasks</th>
    <th>Due Date</th>
    <th>Other</th>
  </header>
  <body>
    <tr>
      <td>1</td>
      <td><b>Monolithic web application with Repository and service layers</b></td>
      <td>
        <b>a)</b> Build REST application on your local computer. Each of you will work own problem.<br> 
        <b>b)</b> Create repository and service layers.<br>
        <b>c)</b> Use Redis for caching.<br>
        <b>d)</b> Do local tests and FTP your application to cloud.<br>
        <b>e)</b> Test your application and observe timing for http requests.<br>
        <b>f)</b> Show that your application runs as required.
      </td>
      <td>17 Oct 2025<br></td>
      <td><a href="pro1_2025.pdf">Project1</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td><b>OAuth2 security and File Upload</b></td>
      <td>
        <b>a)</b> You will add OAuth2 authentication to your project using either Google or GitHub authentication server.<br>
        <b>b)</b> There will be at least two roles: ADMIN and USER. <br>
        <b>c)</b> ADMIN is able to do all CRUD operations over the tables. USER will have limitted access. Create a logic based on your project topic and justify yourself. <br>
        <b>d)</b> Show that a user can upoad an image file. <br>
        <b>e)</b> Show that your application runs as expected.
      </td>
      <td>7 Nov 2025<br></td>
      <td><a href="pro2.pdf">Project2</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td><b>Publishing web project on cloud using Docker-Compose</b></td>
      <td>
        <b>a)</b> You will use Project 2 study as base for this project. <br>
        <b>b)</b> You need to create a cloud account either on AWS or AZURE. You need to create a DockerHub account as well. <br>
        <b>c)</b> Create a jar (or zip for .Net Core). Containerize your app using Docker. Push your app on dockerhub.<br>
        <b>d)</b> Pull your app, Redis and DB in container to the cloud using docker-compose. <br>
        <b>e)</b> Install and set up a reverse proxy web server using Nginx.<br>
        <b>f)</b> Show that your project runs with real IP on the cloud. <br>
      </td>
      <td>28 Nov 2025<br></td>
      <td><a href="pro3-25.pdf">Project3</a></td>
    </tr>
        <tr>
      <td>4</td>
      <td><b>Microservice architecture with Docker-Compose</b></td>
      <td>
        <b>a)</b> Re-design your project in micro-servise architecture as shown in <a href="fig4.pdf">Figure 4</a> <br>
        <b>b)</b> Create Dockerfiles and docker-compose.yaml in your local computer along with your project (services). These will generate containerized app and organize the containers interactions.  <br>
        <b>c)</b> After completing coding and testing of your project in local computer, obtain a jar files and containerized services using proper dockerfiles. <br>
        <b>d)</b> Start up first the separated databases using a compose file by fetching from docker-hub as shown in the class. <br>
        <b>e)</b> Run docker-compose command with your “docker-compose.yaml” file to start your micro-services up. <br>
        <b>f)</b> Use Postman or browser to show your application running as expected. <br>
      </td>
      <td>12 Dec 2025<br></td>
      <td><a href="pro4.pdf">Project4</a></td>
    </tr>
            <tr>
      <td>5</td>
      <td><b>Microservice architecture deployment with Kubernetes cluster</b></td>
      <td>
        <b>a)</b> Obtain jar files, and then docker images for each service using proper dockerfiles. Name image files properly and have them ready in your local repository (no need to push them Docker Hub).<br>
        <b>b)</b> Pull database server image before presentation into your local repository.<br>
        <b>c)</b> Create 2 yaml files for each micro service: One for service app. and the other will be for service database. Use the same image for database server of three services. (PS: You can use the example yaml files given in Sabis.                 Modifying them for your project would be sufficient.)<br>
        <b>d)</b> Presentations will be done on your local computer. Install and start minicube.<br>
<b>e)</b> Start each service using “kubectl” command, for instance “> kubectl create -f service1.yaml”.<br>
<b>f)</b> Test your application using Postman or convinient browser.<br>
      </td>
      <td>26 Dec 2025<br></td>
      <td><a href="pro5.pdf">Project5</a></td>
    </tr>
  </body>
</table>


## General rules for project grading:
* Each student is allowed 20 minutes to present their work.
* Students will be called to present their work based on a random number announced in the class. 
* Students who do not show up at presentation will get 0 (zero) grade.


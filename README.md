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
      <td><b>Basic security and exception handling</b></td>
      <td>
        <b>a)</b> You will use Project 1 study as base for this project. However, the build tool will be Gradle in this time.<br>
        <b>b)</b> Create at least two roles: ADMIN and USER. <br>
        <b>c)</b> ADMIN is able to do all CRUD operations over the tables. USER will have limitted access. Create a logic based on your project topic and justify yourself. <br>
        <b>d)</b> Show that the user image file uploading and displaying them on related web pages work. <br>
        <b>e)</b> Show that your application runs as expected.
      </td>
      <td>7 Nov 2025<br></td>
      <td><a href="pro2.pdf">Project2</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td><b>Publishing web project on cloud using FTP</b></td>
      <td>
        <b>a)</b> You will use Project 2 study as base for this project. <br>
        <b>b)</b> You need to create a cloud account either on AWS or AZURE. <br>
        <b>c)</b> Create a jar (or zip for .Net Core) and ftp it to the cloud. <br>
        <b>d)</b> Have DB service ready/runing on cloud. <br>
        <b>e)</b> Install and set up a reverse proxy web server using Nginx.<br>
        <b>f)</b> Show that your project runs with real IP on the cloud. <br>
      </td>
      <td>21 Nov 2025<br></td>
      <td><a href="pro3.pdf">Project3</a></td>
    </tr>
        <tr>
      <td>4</td>
      <td><b>Publishing web project on cloud using container technologies</b></td>
      <td>
        <b>a)</b> You will use Project 3 study as base for this project. <br>
        <b>b)</b> You need to have a docker-hub account as well as a cloud account either on AWS or AZURE. <br>
        <b>c)</b> Create a jar (or zip for .Net Core) and containerized app using Docker. Push your app on dockerhub.<br>
        <b>d)</b> Pull your app and DB in container on cloud using docker-compose.<br>
        <b>e)</b> Install and set up a reverse proxy web server using Nginx.<br>
        <b>f)</b> Show that your project runs with real IP on the cloud. <br>
      </td>
      <td>5 Dec 2025<br></td>
      <td><a href="pro4.pdf">Project4</a></td>
    </tr>
            <tr>
      <td>5</td>
      <td><b>Microservice architecture</b></td>
      <td>
        <b>a)</b> Create Dockerfiles and docker-compose.yaml in your local computer along with your project (services). These will generate containerized app and organize the containers interactions  <br>
<b>b)</b> After completing coding and testing of your project in local computer, obtain a jar files and containerized services using proper dockerfiles.<br>
<b>c)</b> Push your dockerized apps (docker images) to the DockerHub. <br>
<b>d)</b> Create an EC2 instance on the AWS with minimum settings and Linux OS.<br>
<b>e)</b> Install Docker tools on EC2.<br>
<b>f)</b> Ftp the docker-compose.yaml files to the EC2 instance.<br>
<b>g)</b> Start up first the separated databases using a compose file by fetching from docker-hub as shown in the class.<br>
<b>h)</b> Run docker-compose command with your “docker-compose.yaml” file to start your micro-services up.<br>
<b>i)</b> Observe that required service images are pulled form the hub and starts up correctly.<br>
<b>j)</b> Install Nginx and configure it so the external port 80 will be forwarded to proper services.<br>
<b>k)</b> Show that your application is accessible from remote browser or postman, and everything works properly.
      </td>
      <td>26 Dec 2025<br></td>
      <td><a href="pro5.pdf">Project5</a></td>
    </tr>
  </body>
</table>


## General rules for project grading:
* Each student is allowed 10 minutes to present their work.
* Students will be called to present their work based on a random number announced in the class. 
* Students who do not show up at presentation will get 0 (zero) grade.


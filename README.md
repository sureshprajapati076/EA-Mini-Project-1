# EA-Mini-Project-1

This project has two parts server (spring boot) and client (angular). Please follow following instructions.
This project uses JWT authentication to know who the use is. While running app you can see network tab of chrome to see where the request is forwarded to. Angular for UI.

## Installation

Download zip file attached and extract it. You will find two folders inside MiniProject folder.
Client and Server.

Open terminal. change directory to MiniProject.

Now go to client folder and run following command inside client folder.

```bash
docker-compose up #docker must be installed on your machine

```
You will find client server running on localhost:4200

Next step: go to server folder

```bash
cd ..
cd server
mvn clean # requires maven installed on your machine
mvn install  #creates jar file
docker-compose up
```

You may encounter error. If no error you can run application on localhost:4200
If error encounters on server start. Please run following command again it works.
(This is based on testing my app multiple times. At first run it pulls all required mysql:latest, openjdk:8. if you have already images for mysql and openjdk it will run on first start up)
```bash
docker-compose up

```



## Github link

If maven is not installed on your machine you can download my full project on following link, it has necessary jar file inside target folder.

link to github: [https://github.com/sureshprajapati076/EA-Mini-Project-1](https://github.com/sureshprajapati076/EA-Mini-Project-1) 

## Running App
go to http://localhost:4200
sign up for two users with different role ADMIN and USER
log in with account and follow on screen instructions
Only ADMIN can perform batch job
USER OR ADMIN both can view list of added student records


## Author
* **Suresh Prajapati** 

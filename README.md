# EA-Mini-Project-1

This project has two parts server (spring boot) and client (angular). Please follow following instructions.

## Installation

Download zip file attached and extract it. You will find two folders inside MiniProject folder.
Client and Server.

Open terminal. change directory to MiniProject.

Now go to client folder and run following command inside client folder.

```bash
docker-compose up

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


## Author
* **Suresh Prajapati** 

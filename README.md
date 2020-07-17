# Fire Alarm Monitoring System

## Introduction

This system was developed to help the administration of the fire alarm system to easily handle and monitor fire alarm sensor details such as adding a new sensor to the system update or delete an existing sensor and to display or send all sensor details with respective alerts to end users who are registered in the system for a given time. (if there is a fire detected by sensor alert will be send as an email and a SMS ,Web application users will get updated sensor details for every 40 seconds ,desktop users will receive the updated data for every 30 seconds and all kind of users get updated alerts for every 15 seconds) .So to cater these functionalities ,this system contains with 5 different applications , one REST API one web application one RMI server one desktop client who is using the services of RMI Server and a Sensor Application who provide sensor details by working as multiple sensors(This application consists different threads for every single sensor in the system .These threads work as sensors in runtime to produce sensor details for every 10 seconds ).

## Overview Diagram

![overview](https://user-images.githubusercontent.com/61576355/87778008-2314fd00-c848-11ea-93c3-f8a18edca1ce.jpg)

## Some interfaces of the system

![splash](https://user-images.githubusercontent.com/61576355/87778021-27411a80-c848-11ea-873c-5023220dcd08.png)

![UI1](https://user-images.githubusercontent.com/61576355/87778049-31fbaf80-c848-11ea-883c-21795152e289.png)

![UI2](https://user-images.githubusercontent.com/61576355/87778015-25775700-c848-11ea-9145-5e4b27fc4c9f.png)

![UI3](https://user-images.githubusercontent.com/61576355/87777999-1f817600-c848-11ea-8917-3487f360e71a.png)

![UI4](https://user-images.githubusercontent.com/61576355/87778051-345e0980-c848-11ea-87e1-45630139306c.png)

![UI5](https://user-images.githubusercontent.com/61576355/87778038-2c9e6500-c848-11ea-9c69-6a76563ed040.png)

![UI6](https://user-images.githubusercontent.com/61576355/87778029-2ad4a180-c848-11ea-8a54-176faeb4c68b.png)

## Configurations

### Steps

### 1)Download and extract the zip file

### *Steps to follow for the rest-services-provider project(Rest API + web Client)*

1. This project contains the rest-services-provider(Rest API) and the web client application.<br/>

2. Open project using an IDE(Tested with Intelij IDE) then resolve the dependencies of spring boot and react js applications suing the maven and npm.<br/>

3. After resolving the dependenicies , first run the RestServicesProviderApplication(Spring boot project) class then the REST API will be started.<br/>

4. Then go to the  directory src -> webapp -> front-end ,open a terminal and tyoe npm start command then the web client will start in the port 3000.<br/>
 
### *Steps to follow for DS_Project(RMI server + desktop client)  project*

1. Open the DS_Project in a IDE ,after that add jaxrs-ri and jersey-media-moxy all jar files as external jar files to the project.<br/>

2. Then go to the root directory of the project through a command line and start the rmi registry by typing the command of start rmiregistry on the commandLine.<br/>

3. After that move to com.dsassignement.server package and run the RmiServer class to start the RMI Server.<br/>

4. Then to start the desktop client move to com.dsassignment.client package and run the splash class.

### *Steps to follow for fire-alarm-sensor  project*

1. Open the fire-alarm-sensor project using an IDE and resolve the maven dependencies please import the project as a maven project to the IDE.<br/>

2. Run the SensorHandling class inside com.programmingfoundation.fire_alarm_sensor.controller package to start the application.

## For more inforamtion

YouTube video : https://youtu.be/UGPxCWuqXt4


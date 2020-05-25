# Fire Alarm Monitoring System

Download and extract the zip file 

### Steps to follow for the rest-services-provider project(Rest API + web Client)

1. This project contains the rest-services-provider(Rest API) and the web client application.<br/>

2. Open project using an IDE(Tested with Intelij IDE) then resolve the dependencies of spring boot and react js applications suing the maven and npm.<br/>

3. After resolving the dependenicies , first run the RestServicesProviderApplication(Spring boot project) class then the REST API will be started.<br/>

4. Then go to the  directory src -> webapp -> front-end ,open a terminal and tyoe npm start command then the web client will start in the port 3000.<br/>
 
### Steps to follow for DS_Project(RMI server + desktop client)  project

1. Open the DS_Project in a IDE ,after that add jaxrs-ri and jersey-media-moxy all jar files as external jar files to the project.<br/>

2. Then go to the root directory of the project through a command line and start the rmi registry by typing the command of start rmiregistry on the commandLine.<br/>

3. After that move to com.dsassignement.server package and run the RmiServer class to start the RMI Server.<br/>

4. Then to start the desktop client move to com.dsassignment.client package and run the splash class.

### Steps to follow for fire-alarm-sensor  project

1. Open the fire-alarm-sensor project using an IDE and resolve the maven dependencies please import the project as a maven project to the IDE.<br/>

2 .Run the SensorHandling class inside com.programmingfoundation.fire_alarm_sensor.controller package to start the application.

#### For more inforamtion

YouTube video : https://youtu.be/UGPxCWuqXt4

### Lisence
[MIT](https://opensource.org/licenses/mit-license.html)

# eureka-server-demo
This project is an implementation of eureka server. Every resource servers and consumers could connect to this project for routing purposes.


**How to run**

`java -jar -Dspring.profiles.active=peer-1 demo-0.0.1-SNAPSHOT.jar`

`java -jar -Dspring.profiles.active=peer-2 demo-0.0.1-SNAPSHOT.jar`

`java -jar -Dspring.profiles.active=peer-3 demo-0.0.1-SNAPSHOT.jar`
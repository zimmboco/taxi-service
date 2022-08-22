
# Taxi-service

# Description
- This is a web application that represents the work of a taxi service. It has internal and external parts and is implemented using technologies such as `java`, `java-JSP`, `JDBC` `maven`, `tomcat`, `javax library`, `MySQL`
  Implemented such functions as `registration`, `entry`, `exit`, `creation` and `deletion` of `cars`, `manufacturers` and `drivers`. Implemented a `web filter` to control authorized users.
  A detailed description of the project will be given below.

# Structure : 
- The structure of this project consists of
  - `controller`
  - `dao`
  - `model`
  - `service`
  - `database connections`
  - `web.filter`
  - `webapp`
  

# Used technologies : 
- `java`, `java-JSP`, `JDBC` `maven`, `tomcat`, `javax library` were used for the project, the `MySQL` database was used


# Project start instructions :
  - Create db structure using script from resources/init_db.sql file. 
  - You need to change the database connection settings such as `name`, `url` and `password`. To do this, go to the 
  `taxi/util/ConnectionUtil` folder and change the parameters we need.

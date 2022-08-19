# Taxi-service
- This service allows you to add drivers, cars and car manufacturers. 
You can also add a driver to a specific car, which gives us the opportunity to see which cars we have in the fleet 
and which drivers are responsible for them


- The functions of `registration`, `login`, `logout` are implemented, such functions as: creating a 
`car manufacturer`, creating a `car model` and `linking a driver to a car` are also implemented. Implemented a `web filter` to control authorized users.


- The structure of this project consists of : 
  - `controller` - contains all controllers for working with the web.
  - `dao` - contains the entire implementation of working with databases.
  - `exception` - contains all the necessary exceptions.
  - `lib` - contains everything you need to implement the injector.
  - `model` - contains all the objects for work such as : user, driver and manufacturer 
  - `service` - contains the entire implementation for working with incoming data and processes all requests referring to the dao
  - `util` - database connection settings.
  - `web.filter` - filter to check authenticated users.
  - `views` - implementation of all jsp pages.
  - `web.xml` - links to jsp pages.
  

- technologies such as : `java`, `java-JSP`, `JDBC` `maven`, `tomcat`, `javax library` were used for the project, the `MySQL` database was used


- project start instructions:
  - you need to implement tables for databases. They are in the `resources/init_db.sql` folder. 
  - you need to change the database connection settings such as `name`, `url` and `password`. To do this, go to the 
  `taxi/util/ConnectionUtil` folder and change the parameters we need.
  - connect the `tomcat` and configure it.
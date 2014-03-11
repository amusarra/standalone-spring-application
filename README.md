Standalone JDBC Template Spring Application
=============================

In this repository is available a sample project that shows how easy it is to implement a standalone application 
using the Spring Framework (v. 3.2.2) and is able to manipulate data in a database. 
Access to the database is done using the component's Spring JDBC Template.

This simple project shows how to implement simple CRUD operations (via JDBC Template) on an entity called Horse. The entity is defined as:
* Name: Name of the horse;
* Age: Age of horse;
* Type: Breed of the horse;
* Color Mantle
* Chip Id: ID chip of the horse.
	
The Spring JDBC Template has the following advantages compared with standard JDBC:
* The Spring JDBC template allows to clean-up the resources automatically, e.g. release the database connections;
* The Spring JDBC template converts the standard JDBC SQLExceptions into RuntimeExceptions. This allows the programmer to react more flexible to the errors.

For the configuration of the beans are used exclusively annotations.

Ready to get started? Very well. Follow these steps to run the sample application on the fly.

<pre>	
$ git clone git://github.com/amusarra/standalone-spring-application.git
$ cd standalone-spring-application/
$ mvn package
</pre>
List 1. Clone repository and build the package

<pre>
$ cd target/
$ java -jar standalonespringapplication-jar-with-dependencies.jar
</pre>
List 2. Run the standalone application

Enjoy!

# Java_Project

Problem Statement : To create a user registration application using Spring Boot / JPA / json.

Requirements :

1. To create a user registration form with basic details :
   1.1 Username
   1.2 First name
   1.3 Last Name
   1.4 Email ID
2. Validation of username / API
3. Save the user details 
4. Display the details in json format as output
5. Search by name (Filteration / Specification)

NOTE :

1. The details mentioned above are include as fields in the user registration form.
2. Vaditors have been used as dependencies for validating the username.
3. The details of the users are being saved.
4. The result will be stored in the form of table and can be displayed in json format.
5. To search users by running @Testt code and the desired results can be achieved. 

How to Run the Application : The SbRegistrationFormValidationThymeleafApplication.java file is to be compiled and run at the location
-> $ Java_Project/Java_Project/src/main/java/org/o7planning/sbformvalidation/SbRegistrationFormValidationThymeleafApplication.java 

The default port that Spring Boot runs in is 8080. If you want to change the port for whatever reason, you can set it up in your application.properties file:

server.port = 9090

If you have an IDE like IntelliJ that has extensive support for running Spring Boot projects, then you may go ahead and run it that way. If not, we'll be using the command line to run our project. We can run the application directly by executing ./mvnw spring-boot:run (or ./gradlew bootRun if you're using Gradle) on the command line from your base project folder where pom.xml is located.

Another option is to package your application into a jar file and running it that way.

Spring Boot Angular
========================

Overview:
--------
This is a multi-module Spring Boot Angular 5 starter project. This starter project is just to spare the developers from project setup. 

It has two modules -
1. backend: This contains Spring Boot based backend written in Java.
2. frontend: This contains Angular 5 based frontend of the application. I have also created a couple of basic routes, 
just to provide a starter for routes.

This project compiles the frontend module and creates a jar out of it and then uses that jar in the backend module. 
All of this is managed via maven.

Prerequisite:
------------
Java 8: Download and install the JDK from official website.

Node.js : Download and install the latest version of node.

Angular CLI: It is the official way to bootstrap Angular applications. You can install it using your favourite package manager.

    For npm, you can type npm install -g @angular/cli on your command-line.
    If you use yarn, you can type yarn global add @angular/cli on your command-line.


Running the application:
-----------------------
Step 1. Run 'mvn clean install' at the root project directory:

	xyz\spring-boot-angular>mvn clean install

Step 2. Switch to backend directory and run the Spring Boot app:

	xyz\spring-boot-angular>cd backend

	xyz\spring-boot-angular\backend>mvn spring-boot:run

You can now access the application at: http://localhost:8080


Running only frontend module for UI development:
------------------------------------------------
Go to 'frontend' directory and run below command:

    ng serve

You can now access the UI application at - http://localhost:4200/




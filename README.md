# Base security
How to run 
----------

* Run _Application.java_
* Open [http://localhost:8080](http://localhost:8080)
* Spring Boot will do the rest

Libraries
---------

* Spring Boot 1.4.2
* Thymeleaf for views
* Maven for build

Design
------
* Application - main class  
* MvcConfig - class to configure views and urls  
* WebSecurityConfig - to provide security to resource views  

Resources
------
* '/', '/home' - will run Welcome page
* '/login' - authentication page. Redirects to welcome page after login
* '/hello' - greetings page to signed-in user
* '/admin' - available only for admin
* '/user' - available both for admin, and for user
# guess-the-number
Simple web app that simulate a game where you need to guess the number.

# What I learned ?

  * Model View Controller Design Pattern, Spring MVC and Spring Boot
  
  * Thymeleaf Templates, Thymeleaf Decoupled Logic Fragments
  
  * Using Maven to configure and build multi module projects
  
  * Internationalization to locale language (fr/en)
  
  * Request Interceptor (preHandle, postHandle, afterCompletion)
  
  * Logging with Logback/Slf4j
  
  * Boilerplate code using Lombok 
  
# How to test it ?

 1) Open the file to your IDE
 
 2) Do a mvn clean install 
 
 3) In Web module, run the WebMain class 
 
 4) In your browser type this URL : http://localhost:8080
 
# How to configure number range, and number of guesses: 
 
 1) Go to core module, ressources, config, application.properties
 
 2) set game.minNumber, game.maxNumber and game.guessCount

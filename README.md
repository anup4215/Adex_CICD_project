# CICD_Java_gradle_application

This is a Java Spring Boot web application, and we use Gradle as our build tool. When we compile the code with the command `./gradlew build`, it produces a WAR (Web Application Archive) file. You can deploy this WAR file to a Tomcat server to access and interact with the web application.

Additionally, we have integrated the code with the SonarQube plugin, which allows us to perform static code analysis. By running the command `./gradlew sonarqube`, we can analyze the codebase for code quality and potential issues.
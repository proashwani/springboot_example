add in pom.xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-devtools</artifactId>
</dependency>

- it enabling caching by default to improve
- whenever the changes in the classpath file -  process is also automated restart the server
- spring.thymeleaf.cache=false  (to disable the cache to reflect the changes quickly)
- it includes an embedded LiveReload server that is used to trigger a browser refresh when a resource is changed.
- Any changes made in the project be it a java file change will cause an automated restart of the project:
-  the thread that has spawned the application is not a main rather a restartedMain thread

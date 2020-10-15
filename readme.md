* springboot properties
	run with command
	
	1. mvn plugin
	--------------------
	 a. mvn spring-boot:run (directly run)
	
	 b. mvn spring-boot:run -Dspring-boot.run.arguments="--server.port=8081, --debug=false" (Override properties)
	
	2. production running
	mvn package
	java -jar target/10springexample-0.0.1-SNAPSHOT.jar
	
	3. override the application.properties
	java -Ddebug=false -jar target/10springexample-0.0.1-SNAPSHOT.jar
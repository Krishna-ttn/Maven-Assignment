# Maven-Assignment


Q2: Add a Maven dependency and its related repository URL.

Dependency Added: Apache Commons Lang

Repository URL: https://commons.apache.org/proper/commons-lang/

Q3: Add a new repository in the pom.xml and use its dependencies.

Repository Added: Spring Repo

Repository URL: https://repo.spring.io/release/

Q4: Using JAR plugin, make changes in the pom.xml to make the JAR executable.

Maven Plugin Used: Maven JAR Plugin

Main Class Defined: com.ttn.child1.App

Execution Command: java -jar child1/target/child1-1.0-SNAPSHOT.jar

Expected Output: "Hello from Child 1"

Q5: Differentiate between the different dependency scopes.

Compile Scope Dependency: org.slf4j:slf4j-api

Runtime Scope Dependency: mysql:mysql-connector-java

Test Scope Dependency: junit:junit

Provided Scope Dependency: javax.servlet:javax.servlet-api

Q6: Create a multi-module project and package all modules.

Modules Created: child1, child2

Execution Command: mvn clean package

Expected Outcome: JAR files for all modules.

Referenced URLs

http://maven.apache.org

https://repo.spring.io/release/

https://commons.apache.org/proper/commons-lang/

http://www.slf4j.org/

https://junit.org/junit4/

https://dev.mysql.com/downloads/connector/j/

https://javaee.github.io/javaee-spec/

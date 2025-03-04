# Maven-Assignment
**Q1: Following parameters are to be considered for exercise submission:**

- The complete project has to be submitted.
- .idea, target directories should be excluded
- A text file containing the relevant URLs which are referenced and any other documentation.

**Q2: Add a Maven dependency and its related repository URL.**

Dependency Added: Apache Commons Lang

Repository URL: https://commons.apache.org/proper/commons-lang/

Where is it shown : pom.xml(of parent)


**Q3: Add a new repository in the pom.xml and use its dependencies.**

Repository Added: JitPack Repository

Repository URL: https://jitpack.io

Dependency Used: JitPackDemo from GitHub

GitHub Repository URL: https://github.com/Krishna-ttn/JitPackDemo

Where is it shown: pom.xml (of parent module)


**Q4: Using JAR plugin, make changes in the pom.xml to make the JAR executable.**

Maven Plugin Used: Maven JAR Plugin

Main Class Defined: com.ttn.child1.App

Execution Command: java -jar child1/target/child1-1.0-SNAPSHOT.jar

Expected Output: "Hello from Child 1"

Where is it shown : pom.xml(of child1)


**Q5: Differentiate between the different dependency scopes.**

Compile Scope Dependency: org.slf4j:slf4j-api(SLF4J : used for logging)

Runtime Scope Dependency: mysql:mysql-connector-java(databse connection)

Test Scope Dependency: junit:junit(used for testing)

Provided Scope Dependency: javax.servlet:javax.servlet-api (servlet)

Where is it shown : pom.xml(of parent)


**Q6: Create a multi-module project and package all modules.**

Modules Created: child1, child2

Execution Command: mvn clean package

Expected Outcome: JAR files for all modules.(of child1 and child2)

Where is it shown :target folder contains the jar files(target folder not uploaded on git as per Instructions) child/target contains child1-1.0-SNAPSHOT.jar


**Referenced URLs**

http://maven.apache.org

https://jitpack.io

https://commons.apache.org/proper/commons-lang/

http://www.slf4j.org/

https://junit.org/junit4/

https://dev.mysql.com/downloads/connector/j/

https://javaee.github.io/javaee-spec/



# Group 1 – Maven Build Pipeline Using Azure DevOps

## Experiments 1–4

### Requirements
- Java JDK 17
- IntelliJ IDEA
- Apache Maven
- Git and GitHub
- Azure DevOps

### Common Project Configuration
- Build tool: Maven
- Java version: 17
- Compiler plugin: Maven Compiler Plugin
- Packaging: JAR
- CI/CD platform: Azure DevOps

### Experiment 1: Marks and Grade Calculator
Read marks in three subjects, calculate the average and
display the grade:
- A: 90 and above
- B: 75–89
- C: 50–74
- F: Below 50

### Experiment 2: Electricity Bill Calculator
Calculate electricity bill:
- First 100 units: Rs. 1.50/unit
- Next 100 units: Rs. 2.50/unit
- Above 200 units: Rs. 4.00/unit

### Experiment 3: Simple Interest Calculator
Calculate simple interest using:

SI = (Principal * Rate * Time) / 100

### Experiment 4: Area of Circle
Calculate the area using:

Area = PI * Radius * Radius

### Project Setup
1. Create a Maven Java project in IntelliJ IDEA.
2. Select JDK 17.
3. Copy the required program into Main.java.
4. Configure pom.xml.
5. Compile using Maven.
6. Package the application into a JAR.
7. Execute the JAR locally.
8. Push the source code to GitHub.
9. Connect GitHub to Azure DevOps.
10. Configure and run the Maven pipeline.
11. Verify the generated JAR artifact.

### Maven Commands

Compile:
mvn clean compile

Package:
mvn package

Run:
java -jar target/exp1-1.0-SNAPSHOT.jar

Change the JAR filename according to the experiment.

### Git Commands

git add .
git commit -m "Update experiment"
git push

### Azure Pipeline
The azure-pipelines.yml file builds the Maven project
using JDK 17 and publishes the generated JAR as an artifact.

### Result
The Java application is successfully compiled and packaged
using Maven, and the Azure Pipeline generates the JAR artifact.

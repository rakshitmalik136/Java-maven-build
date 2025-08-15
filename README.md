# DevOps Internship Task 8: Java Maven Build with Jenkins

## Task Overview

The objective of this task was to learn how to build a simple Java application using Maven through Jenkins – an essential step in Continuous Integration and Continuous Deployment (CI/CD) pipelines.

### Tools Required:
- Jenkins
- Java JDK 8 or 11
- Maven
- Git

### Task Details:
- Create a basic Java HelloWorld application
- Prepare a Maven `pom.xml` file to manage the build process
- Configure a Jenkins Freestyle project to build the Java Maven application
- Run the build and verify success via Jenkins console output

---

## How the Task Was Executed

1. **Java Application Creation:**  
   Wrote `HelloWorld.java` with a main method printing a message.

2. **Maven Setup:**  
   Created `pom.xml` specifying project metadata and compiler plugin settings.

3. **Jenkins Configuration:**  
   - Added Maven tool in Jenkins Global Tool Configuration.  
   - Created a Freestyle project.  
   - Configured Git repository link in Source Code Management.  
   - Added Maven build step with goal `clean package` and specified path to `pom.xml`.

4. **Build & Verification:**  
   Triggered Jenkins build and checked console output for `BUILD SUCCESS`.

---

## Deliverables

- Java source code (`HelloWorld.java`)
- Maven build file (`pom.xml`)
- Jenkins Freestyle job configured for Maven build
- Screenshot of successful Jenkins build console output
![Build-Success](screenshots/build-success)


---

*This task enhanced understanding of basic DevOps CI/CD pipelines by integrating Java build automation with Jenkins.*



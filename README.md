# Assignment
User Management API

• GET /user <br>
• POST /user <br>
• PUT /user <br>
• DELETE /user <br>

Pre-Requisite
Java 8 ( >1.8.0_191)

Build and Test 

• Clone from the repo <br>
• Run mvn clean install <br>
• Run mvn clean test <br>
• Run mvn -Dtest=com.uxpsystems.assignment.UserControllerIT test or <br>
• mvn -Dtest=com.uxpsystems.assignment.UserServiceIT test <br>

Run as a standalone web application 
• • Run mvn clean install
• • Locate *.war inside target
• • Run from the command prompt following 
java -jar assignment-0.0.1-SNAPSHOT.war
• • Open the browser/postman 
http://localhost:8080/user/0
• • Prompted for username/password ? enter "systemuser@testdomain.com/password1"
• • Following message should be displayed
{
"message": "User not found : 0",
"errors": null,
"status": "NOT_FOUND"
}

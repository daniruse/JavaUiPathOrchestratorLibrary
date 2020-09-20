# Java UiPath Orchestrator Library
Communicate with UiPath Orchestrator using Java code. Authenticate, start jobs and check results

# Prerequisites
<ol>
  <li><b>Apache HTTP Components</li></b> 
  
If using Maven, include the Apache HTTP Components dependency in the <b>pom.xml</b> file:

 *\<dependency\>\
			\<groupId\>org.apache.httpcomponents\</groupId\>\
			\<artifactId\>httpclient\</artifactId\>\
			\<version\>4.5.10\</version\>\
	\</dependency\>*
  
  Similarly for Gradle, SBT, Ivy etc.
  Alternatively, you can download the JAR file and include it into the classpath from your IDE.
  
 <b><li>org.json</li></b>
 Include dependency in your Java project or add JAR to the classpath:   
 https://mvnrepository.com/artifact/org.json/json/20200518.
 </ol>
 
 Before using this library to connect with UiPath Orchestrator, I strongly encourage you to read more about the most frequent UiPath Orchestrator API calls and OData:
 <ul>
  <li>https://postman.uipath.rocks/?version=latest</li>
  <li>https://docs.uipath.com/orchestrator/reference/authenticating
 </ul>
 Also, keep in mind that the UiPath Orchestrator API implementation may change.
 
 # Usage examples
 Prior to implementing the solution in your project, please try the examples provided in the **Example** Java class.
 
 Before sending requests from Java to the UiPath Orchestrator, the following steps need to be performed:
 <ol>
  <li><b>Retrieve refresh token</b></li>
  

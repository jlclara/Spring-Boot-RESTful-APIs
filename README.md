# Spring-Boot-RESTful-APIs
Basic coding challenge for a job interview. 
Main features: Java, Spring Boot, RESTful API, testing


# API Challenge

Overall business goal: To build a web application that allows users to vote on an object and displays the results
for a set of "objects". 

Your goal:
Build the backend RESTful API in Java for the above business goal. Assume that this API will be used by a different frontend team.

Question: What are the pros and cons of separating FE and BE?
 

# Requirements

The operations we expect to see would be:

* List all of the objects, sorted by creation date
* Vote an object up or down - so that up and down votes cancel one another
* View the total vote count for a given object
* Constraint voting so that each client is allowed to vote at most once for a given object. 

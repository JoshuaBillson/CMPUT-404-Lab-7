# CMPUT 404 Lab 7

**Question 0:** What is the URL of your python flask_restfull code on github???

**Question 1:** Flask is a bare-bones framework that allows us to quickly setup a basic web service but typically requires other libraries to provide features such as authentication, ORM, and form validation. Django provides these and other features out of the box.

**Question 2:** REST stands for "Representational State Transfer". We say that a service is RESTful if it follows a certain convention for referring to objects by URIs and uses HTTP verbs to perform actions on those objects while remaining stateless. Stateless in this context means that whatever state we need is maintained by the client and sent with the request; A RESTful API does not maintain state server-side.

**Question 3:** Create: POST, Read: GET, Update: PUT, Delete: DELETE.

**Question 4:** 1xx codes are informational and simply tell us that the request was received, 2xx codes tell us the request was successfully completed, 3xx codes are used for redirection, 4xx codes are used to denote failures due to client error, and 5xx codes are used to denote failures due to server error.

**Question 5:** XSS stands for "cross site scripting" and is a type of attack that involves injecting javascript into a client-side web application which is then executed by the browser. One means of performing XSS attacks is by entering JavaScript code into any text fields or forms provided by the web page.

**Question 6:** CORS stands for "Cross-Origin Resource Sharing" and is used to restrict the domains from which a JavaScript application running in the browser can make requests to a particular server. You need to worry about CORS any time you are making requests to a backend API from the browser with JavaScript.

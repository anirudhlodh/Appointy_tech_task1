# Appointy_tech_task1
internship selection task for 3rd year VIT Bhopal in Appointy

To run : 

Requirements :

To be able to show the desired features of curl this REST API must match a few requirements:

 GET /users returns list of users as JSON
 
 GET /users/{id} returns details of specific user as JSON
 
 POST /users accepts a new user to be added
 
 POST /users returns status 415 if content is not application/json
 
 GET /admin requires basic auth
 
 GET /users/random redirects (Status 302) to a random user
 
 GET /posts returns list of posts as JSON
 
 GET /posts/{id} returns details of specific posts as JSON
 
 POST /posts accepts a new post to be added
 
 POST /posts returns status 415 if content is not application/json
 
 GET /posts/random redirects (Status 302) to a random post
 
 for example : curl localhost:8080/users -X -d '{"name" : "Anirudh", "id" : "ani", "email" : "anirudhlodh@gmail.com", "password" : "anirudh2001"}' -H "Content-Type: application/json"
 
 run the above command after initialising the server.
 
Data Types :

A user object should look like this:

{"name" : "Anirudh", "id" : "ani", "email" : "anirudhlodh@gmail.com", "password" : "anirudh2001"}

# Friends List Express Application

This project is a friends list application using an Express server with JWT, built in a lab of the IBM Full Stack Software Developer Professional Certificate course on Coursera. It demonstrates CRUD operations on transient data by creating API endpoints with an Express Server that are restricted to authenticated users using JWT and session authentication.
The friends object is a JSON/dictionary with email as the key and a friends object as the value. The friends object is a dictionary with firstName, lastName, and DOB mapped to their respective values. 
Only authenticated users will be able to perform all the CRUD operations.

Routes:
All routes start with /friends
-- GET / (i.e., /friends) Returns a stringified output of the friends object
-- GET /:email (i.e. /friends/a@examples.com) Retrieve a single friend with email ID
-- POST / Add a new fiend which is passed to it via the request body with paraeters email and firstName, lastName, DOB
-- PUT /:email Update the details of a friend with email id
-- DELETE /:email Delete a friend by email id
# Backend Programming challenge

## Evaluation Criteria
 - Working Solution
 - Project organization
 - Clean code
 - Deployment

## Description
  The challenge consists of constructing a backend REST api to expose data. In order to achieve this, you will import a given set of data (look for the solar_data.json file in the data folder) into a database and expose it through a rest api using a node.js server.
  **The server should implement user access control and expose data only to logged users.** You can implement it using whatever mechanism you prefer (token or session based, for instance).
  You should also provide a basic UI for user administration (CRUD). The users entity **must** have at least three fields: **Name**, **email**, and **state**.
  As a requirement, users can only see data from their state.
  It's part of the challenge to create/model an endpoint - will it be a GET or POST request - and how data would be selected using arguments or not. What we want to see here is how you think about modeling the endpoint and why you decided to do it this way. We expected that you are able to put yourself into the api client position's. 

## Requirements
 - Create a readme describing how to run the project
 - Rest endpoints should not return data for logged users only
 - Deploy to a cloud provider of your choice (Heroku, AWS, Azure, Google)
 - Project **must** be versioned using git
 - Back end **must** be done using node.js
 - ### BONUS
   - Test your code
   - Document the API properly

## Submission
 - Create a private git repo online (github or bitbucket)
 - Share the project with us
 

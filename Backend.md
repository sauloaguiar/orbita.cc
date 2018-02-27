# Backend Programming challenge

## Evaluation Criteria
 - Working Solution
 - Project organization
 - Clean code
 - Deployment

## Description
  The challenge consists of constructing a backend REST api to expose data. In order to achieve this, you will import a given set of data (look for the solar_data.json file in the data folder) into a database and expose it through a rest api.
  **The server should implement user access control and expose data only to logged users.** You can implement it using whatever mechanism you prefer (token or session based, for instance).
  The users entity **must** have at least three fields: **Name**, **email**, and **state**.
  As a requirement, users can only see data from their state. If a user tries to access data from another state, the server should return a 401 Unauthorized.
  It's part of the challenge to create an endpoint - `/api/v1/users` - and define how the client can filter data through it. What we want to see here is how you think about modeling the endpoint and why you decided to do it this way. We expected that you are able to put yourself into the api's client position. 

## Requirements
 - Create a readme describing how to run the project
 - Rest endpoints should return data for logged users only
 - Deploy to a cloud provider of your choice (Heroku, AWS, Azure, Google)
 - Project **must** be versioned using git
 - Preferably done using **node.js**
 - ### BONUS
   - Test your code
   - Document the API properly
   - Provide a basic UI for user administration (CRUD)

## Submission
 - Create a private git repo online (github or bitbucket)
 - Share the project with us
 

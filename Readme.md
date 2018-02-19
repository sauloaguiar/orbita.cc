# Programming challenge

## Evaluation Criteria
 - Working Solution
 - Project organization
 - Clean code (both css and js)
 - Deployment

## Description
  The challenge consists of constructing a full software solution to visualize data in a dynamic webpage. In order to achieve this, you will import a given set of data (look for the solar_data.csv file in the data folder) into a database and expose it through a rest api using a node.js server.
  The server should implement user access control and expose data only to logged users. You can implement it using whatever mechanism you prefer (token or session based, for instance).
  The website must contain a dashboard showcasing data from the rest enpoint using graphics from your choice based on the available data (Data Provider, Installation Date,	System Size,	Zip Code,	State,	Cost).
  The website should have two pages: One for login / account setup and another for graphs display.
  **Users can only view data from their own state.**
  
  ### Graphic Suggestions:
   - Cost groupped per data provider / state
   - Number of installations / state

## Requirements
 - Create a readme describing how to run the project
 - Rest endpoints should not return data for non logged users
 - Deploy to a cloud provider of your choice (Heroku, AWS, Azure, Google)
 - Project **must** be versioned using git
 - Front end **must** be done using a SPA framework (React.js)
 - Back end **must** be done using node.js
  - BONUS: Test your code

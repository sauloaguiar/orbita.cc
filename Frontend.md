# Frontend Programming challenge

## Evaluation Criteria
 - Working Solution
 - Project organization
 - Clean code
 - Deployment

## Description
  This goal of this challenge is to assess your ability to build an SPA from scratch using a javascript framework. 
  We provide a json file containing data solar installation (Data Provider, Installation Date,	System Size,	Zip Code,	State,	Cost) and user data that you should use to create/display some graphics. (Our tip here is to use [Json Server](https://github.com/typicode/json-server) to serve the json data in a rest api format.)

  The website should have two pages:
  - One for login / account setup 
  - Another for graphics display
  
  Only logged users should be able to access the graphics area.
  Refer to the provided image as a guide for your implementation.
  We expect you to implement the following visualizations:
  - \# of installs timeline grouped by month/year
  - Installed capacity grouped by month/year
  - Cost grouped by month/year

  Also, following the provided image, the bottom squares should contain the following information
  - \# of installs in the period
  - Data about the biggest (cost or size wise) installation
  - Data about the top three companies (those who have more installs)
    Company name
    total capacity installed

## Requirements
 - Create a readme describing how to run the project
 - Deploy to a cloud provider of your choice (Heroku, AWS, Azure, Google)
 - Project **must** be versioned using git
 - Front end **must** be done using a SPA framework (React.js) 
 - ### BONUS
   - Test your code
   - Add a dropdown/datepicker to select the date period to be considered

## Submission
 - Create a private git repo online (github or bitbucket)
 - Share the project with us
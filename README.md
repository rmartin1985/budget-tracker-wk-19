# budget-tracker-wk-19

  ![](https://img.shields.io/badge/license-MIT-blue)

  ## Description
 If it is one thing that is universal in this day and age, it is the need to be able too accurately keep track of one's finances. With almost every purchase we make being digital, someone can really lose track of how much money they have and how much they are spending. Before all of this, people would have to physically write down their transactions in order to properly balance their accounts. 

 Luckily this week we were challenged to help with an app that would help someone track their budget. Even further, we want to make sure that this Budget Tracker app can be used when the user is offline and to have the ability to use this as a Progressive Web App (PWA) so that they can actually download this application as if it was a native app from an App store on the phone. 

 The basic functionality of the app was already provided for us with the starter code. 

 First I had to create a file for the IndexDB to connect. Then I created a service workers file to instruct the browser what to do with the files depending on the level of connectivity the user has at that given time.

 Now when someone uses this app, they can include their transactions whether they have an internet connection or not. The info is saved and will load upon getting connection again.  

  ## Table of Contents
  1. [Installation](##installation)
  2. [User Story](#user-story)
  3. [Acceptance Criteria](#acceptance-criteria)
  4. [Deployed Application](#deployed-application)
  5. [Demo](#demo)
  6. [Technology](#technology)
  7. [Questions](#questions)
  8. [License](#license)
  

  ## Installation
  1. Fork this repository
  2. Clone repository to your local directory
  3. Make sure you have installed Node.js 
  4. Run npm install to install the necessary dependencies
  ```
  npm install
  ```
  5. Start the server by typing "npm start" and open localhost:3001
  ```
  npm start
  ```

  ## User Story
  ```
  AS AN avid traveler
  I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
  SO THAT my account balance is accurate when I am traveling 
  ```
  ## Acceptance Criteria
  ```
  GIVEN a budget tracker without an internet connection
  WHEN the user inputs an expense or deposit
  THEN they will receive a notification that they have added an expense or deposit
  WHEN the user reestablishes an internet connection
  THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

  ```

  ## Deployed Application
  Please click the following link  to be taken to a Heroku app of this application: 
  [Budget-Traker](https://warm-chamber-52689.herokuapp.com/)

  ## Demo
  Click the link below to be taken to a video that will demo the basic functions of this budget tracker app. 

  [Budget-Tracker](https://drive.google.com/file/d/1A7664Ib8GvDtny-kDmDpRZBFR84b5y99/view)

  ## Technology Used
  **1. [Node.js](https://nodejs.org/en/)**

  **2. [MongoDB](https://www.mongodb.com)**

  **3. [Mongoose ODM](https://mongoosejs.com/)**

  **4. [Express.js](https://www.npmjs.com/package/express)**

  ## Questions

  If you have any questions regarding this project, you can reach me at my GitHub account or by email at:
  <br />
  Github: [rmartin1985](https://github.com/rmartin1985)
  <br />
  Email: rickmartinatx@gmail.com

  ## License
  Licensed under the [MIT License](LICENSE)
# Crypto Source Pro
  ## Description  
  This is a project that allows users to dynamically track their crypto assets. It uses express-session authentication to create a unique account. Once the account is created a wallet page will load where you can add different crypto currencies as well as the amount you own in to the wallet. The application will then calculate the price of your holdings based on the current value of the crypto currency added.  

  ## TECHNOLOGY USED

  HTML, CSS, Bulma, Javascript, Sequelize, Sequelize CLI  
   

  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)

  ## Installation
  The project is deployed on heroku so you should be able to simply load the application from the link at the bottom of the readme and use it successfully. If you would like to play around with the source code be sure to install the required packages using npm install. Create a .env variable and to store the necessary MySQL variables, assuming you already have SQL installed. In order to seed the coin table follow the directions listed below.

  To seed the coin table, first install the sequelize CLI by running the command 'npm install --save-dev sequelize-cli' from your terminal. Next, type 'npx sequelize db:seed --seed 20220403004935-coin-seeder.js' to seed the table. If you accidentally run the seeder more than once simply type the command 'npx sequelize db:seed:undo:all' to undo your changes. If you undo the seeds you need to flush the table data by changing the force: false to force: true in server.js and run the command node server.js. Then change the force: true back to force: false to keep any new data. To reseed the Coin table re-enter the command 'npx sequelize db:seed --seed 20220403004935-coin-seeder.js'. 

  
  ## Usage
  From the bash terminal invoke an instance of the server using node server.js or npm start. From there, use software sucha as Insomnia to test the existing routes or your own newly created routes. If you want to see the webpage locally go to your localhost:3001/ once the server has started.

  
  ## License: None

  
  ## How to Contribute
  If you add anything you think is cool request to push to the repo and I will review the code. If it seems worthy I'll merge it.

  
  ## Tests
  No tests are currently implemented for the app

  
  ## Questions
  Links below are to my GitHub profile and email.
  Feel free to contact me with any questions you may have about the application  
  GitHub: [dreina99](https://www.github.com/dreina99)  
  Email: [devinreina99@gmail.com](mailto:devinreina99@gmail.com)

  ## Link
  https://calm-island-91676.herokuapp.com/

  ## Contributors
  Andew Nohr, Christopher Palileo, Jason Greena, Devin Reina, Giang Nguyen, Sally Chan

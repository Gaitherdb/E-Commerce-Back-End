# E-Commerce Back End
  ## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

  ## Description
  An application that is the back end for an acting e-commerce site. Built with JavaScript, the app uses an Express.js API to use Sequelize to interact with a MySQL database. The app stores categories, products, and tags in the database, and functions to retrieve the desired information about each table and their corresponding tables, while also being able to make edits.  
  
  Using Insomnia, an API client, a user is able to GET, GET by ID, POST, PUT by ID, & DELETE by ID either a category, product, or tag. When editing a product or a tag, or a product or a category, one is able to also include the corresponding id. 

  While creating this app, I used MySQL to source my schema database, Node.js to run the server javascript file which makes my data live and editable via an API client.

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Questions](#questions)
  
  ## Installation
  To install Node.js, follow the documentation [Node.js](https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs)

  To install MySQL, follow the documentation [MySQL](https://dev.mysql.com/downloads/installer/)

  To install necessary dependencies, run the following command: 
  ```
  npm i
  ```
  
  ## Usage
  Set the path to the E-Commerce-Back-End folder in the terminal and log in to MySQL and source the schema.sql by running `source db/schema.sql`. Run `Node seeds/index.js` to source the seeds folder, if you want preset data.  Then run the server.js file by typing `node server.js`. Access the API data through an API client like Insomnia with GET, POST, PUT, & DELETE.

  Walkthrough video: [Walkthrough](https://drive.google.com/file/d/1soruGKeTdcG8MpBLWYpwO_SLj0rBRGgn/view)

  ## License  
  This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

  ## Contributing
  I am the sole author of this repo and I am not currently looking for contributors.


  ## Questions
  If you have any questions about the repo, open an issue or contact me directly at Gaitherdb@gmail.com. You can find more of my work at [Gaitherdb](https://github.com/Gaitherdb).
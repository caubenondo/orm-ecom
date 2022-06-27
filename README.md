# E-commerce Database with ORM
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Description
  This application will build the back end for an e-commerce site using Object Reational Mapping models.

  ## Table of Contents
  * [Installation](#Installation)
  * [Usage](#Usage)
  * [License](#License)
  * [Contributing](#Contributing)
  * [App in Actions](#Tests)
  * [Questions](#Questions)

  ## Installation <a name='Installation'></a>
  To install necessary dependencies, run the following command:
  ###### Install npm packages
  ```
    npm i
  ```
  
  ###### Create database in mySQL
 ```
    mysql -u <username> -p
 ```
 ```
    source ./db/schema.sql
 ```
 ###### Connect mySQL database with .env file
  ```
    DB_USER=''
    DB_PW=''
    DB_NAME='ecommerce_db'
  ```
 ###### Seed database with default data
```
npm run seed
```
###### Start server
```
npm run start
```
  ## Usage <a name='Usage'></a>
  This project use MySQL2 and Sequelize packages to connect Expressjs API to a MySQL database and the dotenv package to use environment variable to store sensitive data.
  
  ## License <a name='License'></a>
  The project is under [MIT](https://opensource.org/licenses/MIT) license.

  ## Contributing <a name='Contributing'></a>
  If you want to contribute to this project, feel free to contact me (info below).

  ## App in Actions <a name='Tests'></a>
  Please watch [Video](https://youtu.be/0CmvAMUpZDQ) to review app in actions.

  ## Questions <a name='Questions'></a>
  If you have any questions about the repo, open an issue or contact me directly at caubenondo@gmail.com.
  You can find more of my work at [caubenondo](https://github.com/caubenondo)

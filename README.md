# Table of Content

[1. Noted](#noted)

[2. Get Started](#get-started)

[3. Database](#database)

[4. Available Scripts](#available-script)

[5. Postman](#postman)

#1. Noted

* node.js version `v12.18.3`
* npm version `8.1.2`
* npx version `10.2.2`

# 2. Get Started

## Installation 
```
  npm install
```

## Install sequelize-cli
```
  npm install -g sequelize-cli
```

### * Noted
* To run the project we need to add one more file (.env file)

* When you installed npm above 5.2.0 version then automatically npx will installed. It is an npm package runner that can execute any package that you wnat from the npm registry without even installing that package. If you have installed npm below 5.2.0 then npx is not installed in your system.  You can check npx is installed or not by running the following command:

```
  npx --version
```

If npx is not installed you can install that separately by running the below command:

```
  npm install -g npx
```

## Install bcrypt
```
  npm i bcrypt
```

# 3. Database

## Create database directly


Download Navicat: https://getintopc.com/softwares/development/navicat-premium-2020-free-download/

* Noted
Database name and Password must be follow the .env file


## Create database by command

You can create database by following the command below:

```
  npx sequelize-cli db:create
```
## Set database url

* You can set database url by running the command:

set [Databae-Url from .env file]

* Display the current node environment

```
  echo %NODE_ENV%
```
Then it will output the environment on the command line like: development

# 4. Available Scripts

## Database migration 
You need to migrate the database following the command below: 

```
  npm run migrate
```
## Run project
* Development
Start the application in the development mode 
```
  npm run dev
```

* Production
Start the application for production
```
  npm run start
```

# 5. Postman
- Download postman

You can download postman here: https://www.postman.com/downloads/

- Import postman url

Postman url: https://www.postman.com/collections/d4bf2fcfb0f9938944d4


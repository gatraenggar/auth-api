# Auth-API
## What is this ?
A source code consists of authentication feature built on REST API which is used as a source for GitHub Action implementation.

This repository is built as a CI/CD learning demo of Dicoding's Becoming Backend Expert module. This Dicoding module is divided into two segments which each segment has its own project submission. This repository is a part of the 2nd segment which teach about CI/CD using GitHub Action, Security (eg. SQL injection, DDoS attack, Man in The Middle), and server scalability.

## How to test this in local environment ?
### Installation
#### 1. `git clone https://github.com/gatraenggar/auth-api.git`
#### 2. `cd auth-api`
#### 3. `npm install` to install the all dependency needed

### Configuration
#### 5. Create a PostgreSQL database
#### 4. Change user, password, & database value in config/database/test.json file based on yours
#### 6. Change user, password, & database value in .env file based on yours

### Run the App
#### 7. `npm run migrate:test up` to migrate/create the database table
#### 8. `npm run test:watch` to run the test

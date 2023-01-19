# Online Voting System

It is an Online Voting Application built by using Node.js,Express JS(EJS) 
It consists of two user roles... 1)admin 2)Voter admin : admin can create multiple elections, each election consist of multiple questions. admin adds the voters by giving voter ID and password. After creating questions and voters, admin can launch the election and it provides publicURL where voters can vote through using publicURL. At last admin ends the election and checks the results. Voter : Voter visits the publicURL given by the admin. Login by using default credentials by admin. After login voter can be albe to vote for the question and submit the result.

## Features
- Admin will be able to signup
- Admin can create multiple elections
- Admin can create a ballot of questions in an election
- Admin can register voters
- Admin can launch an election
- Reset password feature for both admin and voter
- Elections administrator can set custom path to election
- Uses CSRF tokens to prevent attacks 


## Installation

Don't forget to create the databse with corresponding name as mentioned in `config.json`

Go to the project directory

Install dependencies

```bash
  npm install
```
or
```bash
  npm i
```
start server to run the website in localhost

## Start server

```bash
  npm start
```
## To create database

To create database,run the following command

```bash
npx sequelize-cli db:create
```
## To migrate database

To migrate database,run the following command

```bash
npx sequelize-cli db:migrate
```

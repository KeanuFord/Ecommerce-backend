
# Ecommerse Backend 

## Description
This is a database for an ecommerse business that tracks products, categories of products, as well as grouping tags for the products

## Video Demo
https://drive.google.com/file/d/1XLfwYNJKZ2T7rSbTvl2H8CbYNk9-_KAp/view?usp=sharing
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribution](#contribution)
- [Testing](#testing)
- [Contact](#contact)

## Installation
First run this command in the main directory:
``` 
npm i
```
Next you're going to use the schema to create a database.

* First initialize psql with your username using this command. After this it will prompt you for your password
```
psql -U postgres
```
* After entering your password enter this command to run the schema file inside the db directory
```
\i db/schema.sql
```
* Next exit postgres
```
\q
```
Before running the server, ensure you have a `.env` file filled it with your postgres username and password. The file should include these lines
```
DB_NAME='ecommerce_db'
DB_USER=''
DB_PASSWORD=''
```

Next you can either seed it for testing purposes by running `npm run seed` or you can launch it as is using this command:
```
node server.js
```
It is recommended to use Insomnia to test all the necessary network requests

## Usage
The functionality of this app is to keep a track of an Ecommerse inventory. It is recommended to use the Insomnia app to test all the necessary network requests.

Link to video demo: https://drive.google.com/file/d/1XLfwYNJKZ2T7rSbTvl2H8CbYNk9-_KAp/view?usp=sharing

## Licence [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
MIT

## Contribution
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](https://www.contributor-covenant.org/)

## Contact

Email: KeanuF2017@gmail.com
Github: https://github.com/KeanuFord

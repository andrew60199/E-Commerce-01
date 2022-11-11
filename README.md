# E-Commerce Back-end

## Description

This repository holds the beginnings of an E-Commerce application. Focusing on the functionality of the back-end server and database. Using MySQL through Sequelize the developer experience is significantly improved. Allowing programmers to write in an object-oriented way using JavaScript. 

The routes allow the user to perform RESTful CRUD operations. Making it easy to retrieve, post, update and delete data on the database. 

<img src="https://img.shields.io/badge/licence-Apache%20License%202.0-blue">

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)
- [Tests](#tests)
- [License](#license)

## Installation

Clone this repository, run npm i to install the necessary node modules. 

## Usage

Checkout the walkthrough video showing the back-end functionality with mock data.

https://drive.google.com/file/d/1ovTNZb_MYEoH34Uzq80FlQO1WlKmvFKN/view?usp=sharing

The routes set up are:

- api/products
- api/products/:id
- api/categories
- api/categories/:id
- api/tags
- api/tags/:id

All of which can be used with the GET, POST, PUT and DELETE methods.

The JSON object to POST and PUT are as follows:

- Products
```
{
      "product_name": "<name>",
      "price": <price>,
      "stock": <stock on hand>,
			"category_id": <category id>,
			"tagIds": [<tag id>]
}
```
- Categories
```
{
	"category_name": "<name>"
}
```
- Tags
```
{
	"tag_name": "<name>"
}
```

## Contribution

N/A

## Tests

N/A

## License

This project is covered under the Apache License 2.0 which you can read in depth here https://spdx.org/licenses/Apache-2.0.html
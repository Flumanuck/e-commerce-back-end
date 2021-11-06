# E-Commerce Back End

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)
- [Video-Example](#video-example)

## Description

This is a back-end application that allows the user to access a database and view, edit, and delete items using a program such as Insomnia or Postman.

## Installation

From the command line, run "npm i" to install the needed dependencies.

## Usage

- Run "npm start"
- Below is a list of endpoints you can use with Insomnia/Postman

  | Method | Endpoint            | Description                           | Requires                   |
  | ------ | ------------------- | ------------------------------------- | -------------------------- |
  | GET    | /api/products       | Returns products including categories | n/a                        |
  | GET    | /api/products/:id   | Returns product with matching id      | n/a                        |
  | POST   | /api/products       | Creates new product                   | product_name, price, stock |
  | PUT    | /api/products/:id   | Updates product with matching id      | All fields being updated   |
  | DELETE | /api/products/:id   | Deletes product with matching id      | n/a                        |
  | GET    | /api/tags           | Returns tags including products       | n/a                        |
  | GET    | /api/tags/:id       | Returns tag with matching id          | n/a                        |
  | POST   | /api/tags           | Creates new tag                       | tag_name                   |
  | PUT    | /api/tags/:id       | Updates tag with matching id          | All fields being updated   |
  | DELETE | /api/tags/:id       | Deletes tag with matching id          | n/a                        |
  | GET    | /api/categories     | Returns categories including products | n/a                        |
  | GET    | /api/categories/:id | Returns category with matching id     | n/a                        |
  | POST   | /api/categories     | Creates new category                  | category_name              |
  | PUT    | /api/categories/:id | Updates category with matching id     | All fields being updated   |
  | DELETE | /api/categories/:id | Deletes category with matching id     | n/a                        |

## Screenshot

![screenshot of insomnia data](https://github.com/Flumanuck/e-commerce-back-end/blob/main/Screenshot.PNG?raw=true)

## Video-Example

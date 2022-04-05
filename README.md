# E-commerce Back End Database 

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Description 
- Database model for an e-comnerce store
- Allow ability to view, and update products, their categories, and tags
- Create new products, update inventory, delete products

[DEMO VIDEO](https://drive.google.com/file/d/1cHL_kCMHnB3_bBB4krgz8_8zGzs3C7ik/view?usp=sharing)

## Installation 
- Clone the repository 
- run "npm init" or "npm -y init"
- install dependencies - ($ npm i dotenv express mysql sequelize")
- Create a .env file and populate with your SQL credentials:

```
DB_NAME='ecommerce_db'
DB_USER='MySQL username'
DB_PW='MySQL password'
```
- Open MySQL shell and sign in
- $ source db/schema.sql, then quit
- $ npm run seed
- $ npm start
- http GET, POST, PUT, DELETE routes include
  - /api/categories
  - /api/categories/${id}
  - /api/products
  - /api/products/${id}
  - /api/tags
  - /api/tags/${id}

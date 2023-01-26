# E-Commerce Backend (ORM)

This backend is built using Object Relational Mapping (ORM) to handle database operations. It is designed to support the basic functionality of an e-commerce website, such as managing products, orders, and customers.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Getting Started](#getting-started)
- [Video Link](#video-link)
- [Further Development](#further-development)
- [Contribution](#contribution)

## Technologies Used
- Node.js
- Express.js
- MySQL

## Features
- Product management: Ability to add, update, and delete products.
- Order management: Ability to view, update, and delete orders.
- Customer management: Ability to view, update, and delete customer information.

## Getting Started

1. Clone the repository
```
git clone
```
2. Install dependencies
```
npm install
```
3. Create a .env file in the root directory and add the following:
```
DB_USER=your_mysql_username
DB_PW=your_mysql_password
DB_NAME=ecommerce_db
```
4. Run the following command to create the database:
```
npm run seed
```
5. Start the server
```
npm start
```
6. Open Insomnia Core to test the API routes.

## Video Link
You can view the video [here!](https://drive.google.com/file/d/1aH1r_6Rmnz4tMhpNCzbjQdYx6nonleUX/view?usp=sharing)

## Further Development

- Add authentication and authorization.
- Implement pagination for API endpoints that return multiple items.
- Add search functionality for products.
- Implement a shopping cart feature.

## Contribution

Feel free to contribute to this project by submitting pull requests.

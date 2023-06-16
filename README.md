# E-Commerce-Backend

This is the backend for an e-commerce site. The application can GET, POST, PUT, and DELETE data for various routes (categories, products, and tags) using the Insomnia REST API client.

## Built with

- [Javascript](https://www.javascript.com/)
- [Node.js](https://nodejs.org/en/)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [MySQL2](https://www.npmjs.com/package/mysql2)

## Installation

To get started clone this repository using
<br>

```terminal
git clone <repository-url>
```

Both Node.js and MySQL must be installed on your computer.

Install dependencies

```terminal
npm init --y
npm install express sequelize mysql2
```

Open up MySQL shell and input

```terminal
source db/schema.sql
use ecommerce_db
```

Then quit MySQL shell and input the following in your terminal

```terminal
npm run seed
```

to start running application simply input

```terminal
node server.js
```

Now, you can use Insomnia Core to GET, POST, PUT, and DELETE data from different routes.

## API Client

[Insomnia](https://insomnia.rest/)

## Demo

![](./images/demo.gif)

## Contributor

Erik Williams

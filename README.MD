# ShopHub Ecommerce MERN APP

> This is an eCommerce web application created with MongoDb, Express, React & Node Stack. It has user authentication system, an admin user who can add new products in the app, check for order and payments and also choose which order has been delivered from the store. It is deployed in Vercel and below you can find the link to visit the app.

## Live Preview Project

- Click Production Link Below
  [ShopHub](https://shophub-mern-portfolio.vercel.app/)

## Built with

- NodeJs
- Express
- ReactJs
- Redux
- MongoDb
- React Hooks
- React Bootstrap
- Axios
- Bcrypt
- JSON Web Tokens
- Prettier
- Eslint
- React Helmet

## Features

- Fully featured Shopping Cart
- Product Reviews and Ratings
- Top Products Carousel
- Product Pagination
- Product Search Feature
- User Profile with Orders
- Admin Product Management
- Admin User Management
- Admin Order Details Page
- Mark Orders as Delivered Option
- Checkout Process (Shipping, Payment Method, etc)
- PayPal / Credit Card Integration (Removed Due to Dependency Conflict)
- Database seeder (Products & Users)

## Usage

### ES Modules in Node

We use ECMAScript Modules in the backend in this project. Be sure to have at least Node v14.6+ or you will need to add the "--experimental-modules" flag.

Also, when importing a file (not a package), be sure to add .js at the end or you will get a "module not found" error

You can also install and setup Babel if you would like

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev
# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import
# Destroy data
npm run data:destroy
```

### Sample User Logins

```
admin@example.com (Admin)
123456
jane@example.com (Customer)
123456
```

[Login/Register ShopHub](https://shophub-mern-portfolio.vercel.app/register?redirect=/)

## Author

- Github: [@noahmuler](https://github.com/noahmuler)
- LinkedIn: [@itxSaaad](https://linkedin.com/in/itxSaaad)


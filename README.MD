# ShopHub Ecommerce APP

> This is an eCommerce webstack application created with MERN (MongoDb, Express, React & Node) Stack. 

> Application includes: 
- user registration with authentication
- user with admin access can add new products
- monitoring order and payment
- monitoring which order has been delivered from the store


## Live Preview Project

It is deployed in Vercel and below you can find the link to visit the app.

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
- LinkedIn: [@noah-taddese](https://www.linkedin.com/in/noah-taddese-094406188)

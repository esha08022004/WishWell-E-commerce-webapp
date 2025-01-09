# E-Commerce Platform

A robust and scalable **E-Commerce Platform** built using modern web technologies, ensuring secure transactions, fast performance, and an intuitive user experience.

## Features

### 1. **MongoDB & Redis Integration**
- **MongoDB** for data storage, handling users, products, and orders.
- **Redis** for caching to improve data retrieval performance.

### 2. **Stripe Payment Setup**
- Integrated **Stripe** for secure and seamless payment processing.

### 3. **Authentication & Security**
- **JWT-based Authentication** for user login and signup.
- Supports **access and refresh tokens** for secure and persistent sessions.
- Data protection with encryption and security best practices.

### 4. **Core E-Commerce Features**
- **Product & Category Management**: Add, update, and manage products and categories.
- **Shopping Cart**: Add/remove items, view cart, and proceed to checkout.
- **Coupon Code System**: Apply discount codes during checkout.

### 5. **Admin Dashboard**
- User-friendly interface for admins to manage products, orders, and view **Sales Analytics**.

### 6. **Responsive Design**
- Built with **Tailwind CSS** for a modern, responsive, and visually appealing UI.

## Tech Stack

- **Backend**: Node.js, Express.js, MongoDB, Redis
- **Frontend**: React.js, Tailwind CSS
- **Authentication**: JWT (JSON Web Tokens)
- **Payments**: Stripe API
- **Caching**: Redis

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- Redis

  ### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-platform.git
   cd ecommerce-platform
   ```

2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```

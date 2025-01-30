# Bicycle Store Application

## Project Overview

The **Bicycle Store Application** is a full-stack e-commerce platform designed for seamless bicycle purchases. It provides role-based authentication, product management, and secure payment integration. The application ensures a smooth user experience, responsive design, and data security.

## Features

### 🔐 User Registration & Authentication

- Secure user registration with name, email, and password.
- Passwords are securely hashed before being stored.
- Role-based authentication (default: customer, admin manually assigned).
- Users can log in via email and password.
- **JWT Authentication** for session management.
- Logout feature to remove JWT token and redirect to login.

### 🌍 Public Routes

#### Home Page

- **Navbar:** Logo, navigation items, and authentication buttons.
- **Banner Section:** Special offers and promotions.
- **Featured Bicycles:** Display up to 6 bicycles with a "View All" option.
- **Extra Section:** Testimonials or other e-commerce-related content.
- **Footer:** Important links, social media icons, and contact details.

#### All Bicycles Page

- **Search Functionality:** Search by brand, name, or category.
- **Filters:** Price range, model, brand, category, and availability.
- **Dynamic Results:** Updates based on search and filter selections.
- **Bicycle Cards:** Display details including name, brand, model, price, and category.

#### Bicycle Details Page

- Displays product image and full specifications.
- "Buy Now" button redirects to the checkout page.

#### About Page

- Provides details about the bicycle store and its mission.

### 🔒 Private Routes

#### Checkout Page

- Allows users to order bicycles.
- Ensures ordered quantities do not exceed available stock.
- **Order Form:** Includes product details, user details, total price calculation, and payment method.
- **Payment Integration:** Supports SurjoPay, Stripe, or other payment gateways.
- "Order Now" button finalizes the purchase.

#### Dashboard (Role-Based Access)

- **Admin Dashboard:** Manage users (deactivate accounts), products (CRUD operations), and orders.
- **User Dashboard:** View orders and manage profile settings.
- Users can update passwords securely (requires the current password for validation).

## 📌 Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Firebase, JWT
- **Hosting & Deployment:** Vercel / Netlify
- **Payment Gateway:** SurjoPay / Stripe

## 🚀 Installation & Setup

### Backend Setup

```sh
cd server
npm install
npm start
```

### Frontend Setup

```sh
cd client
npm install
npm start
```

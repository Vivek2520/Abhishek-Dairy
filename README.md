# Abhishek Dairy & General Store

A modern e-commerce website for a neighborhood Kirana store in Waidhan, Singrauli, Madhya Pradesh.

## Features

- 🛍️ Product Catalog with Search & Filter
- 🛒 Shopping Cart with LocalStorage
- 📱 Mobile Responsive Design
- 🎨 Beautiful UI with Tailwind CSS
- 💬 WhatsApp Integration for Orders
- 🔧 Backend API for Product and Order Management

## Live Website

https://abhishek-dairy-store.netlify.app

## Technologies Used

### Frontend

- HTML5
- Tailwind CSS
- JavaScript (Vanilla)
- Font Awesome Icons

### Backend

- Node.js
- Express.js
- CORS

## Backend API

The backend provides RESTful API endpoints for managing products and orders.

### Products

- `GET /api/products` - Get all products (with optional category and search filters)
- `GET /api/products/:id` - Get a single product by ID
- `GET /api/categories/:category` - Get products by category

### Orders

- `POST /api/orders` - Create a new order
- `GET /api/orders` - Get all orders
- `GET /api/orders/:orderId` - Get a specific order by ID

### Health Check

- `GET /api/health` - Check server status

## Contact

📞 Phone: 7879355368, 7000755886
📍 Address: Dhotti, Sai College Road, Waidhan, Singrauli, Madhya Pradesh 486886
🕐 Hours: Monday - Sunday, 8:00 AM - 10:00 PM

## Local Setup

### Frontend

1. Clone the repository
2. Open `index.html` in your browser
3. No dependencies required!

### Backend

1. Ensure Node.js is installed
2. Install dependencies: `npm install`
3. Start the server: `npm start` (or `npm run dev` for development)
4. The API will be available at `http://localhost:5000`

## Deployment

Deployed on Netlify with automatic deployments from GitHub.

## License

© 2024 Abhishek Dairy & General Store. All rights reserved.

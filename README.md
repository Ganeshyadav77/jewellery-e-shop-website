# 💎 Jewellery E-Shop Website

A full-stack e-commerce application for an online jewelry boutique. Features user authentication, cart management, product catalog, and payment integration.

## 📋 Table of Contents

- [Live Demo](#live-demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## 🌐 Live Demo

### ✨ Experience the Live Application

**[🔗 View Live Demo](https://ganeshyadav77.github.io/jewellery-e-shop-website/)** - Experience the luxury jewelry collection in action!

This live demo showcases a fully functional jewelry e-commerce platform with a beautiful, responsive interface. Explore our premium collection and experience the seamless shopping journey.

### 🎯 Live Demo Features:
- 🛍️ **Browse Premium Jewelry** - Explore our exquisite collection of jewelry products
- ❤️ **Wishlist Management** - Save your favorite items to your wishlist
- 🛒 **Shopping Cart** - Add items to cart and manage quantities
- 🔍 **Advanced Search & Filter** - Find jewelry by category, price range, and more
- 📱 **Fully Responsive Design** - Perfect experience on desktop, tablet, and mobile devices
- 💬 **WhatsApp Support** - Connect with our team for inquiries and support
- 🎨 **Beautiful UI/UX** - Modern and intuitive user interface design
- ⚡ **Fast Performance** - Optimized for quick loading and smooth navigation

### 🔗 Demo Link
- **Live URL**: https://ganeshyadav77.github.io/jewellery-e-shop-website/
- **Status**: ✅ Active and Running

---

## ✨ Features

- **User Authentication**: Secure login and registration system
- **Product Catalog**: Browse jewelry items with detailed descriptions and images
- **Shopping Cart**: Add/remove items and manage quantities
- **Payment Integration**: Secure payment processing
- **Order Management**: Track orders and order history
- **User Profile**: Manage user information and preferences
- **Search & Filter**: Find jewelry by category, price, and more
- **Responsive Design**: Works on desktop and mobile devices

## 🛠️ Tech Stack

### Frontend
- HTML5, CSS3, JavaScript
- React (or your framework choice)
- Redux/Context API for state management
- Bootstrap/Tailwind CSS for styling

### Backend
- Node.js & Express.js
- MongoDB/PostgreSQL for database
- JWT for authentication
- Stripe/PayPal for payment integration

### Tools & Services
- Git & GitHub for version control
- npm/yarn for package management

## 🚀 Installation

### Prerequisites
- Node.js (v14+)
- npm or yarn
- MongoDB/PostgreSQL installed
- Git

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ganeshyadav77/jewellery-e-shop-website.git
   cd jewellery-e-shop-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Setup environment variables**
   ```bash
   cp .env.example .env
   ```
   Update `.env` with your configuration:
   - Database credentials
   - API keys (Stripe, PayPal, etc.)
   - JWT secret

4. **Start the development server**
   ```bash
   npm start
   # or
   yarn start
   ```

5. **Access the application**
   Open [http://localhost:3000](http://localhost:3000) in your browser

## 📖 Usage

1. **Browse Products**: Navigate to the shop to view jewelry collections
2. **Create Account**: Sign up or login to your account
3. **Add to Cart**: Select items and add them to your shopping cart
4. **Checkout**: Proceed to payment with secure checkout
5. **Track Orders**: View your order history and status

## 📁 Project Structure

```
jewellery-e-shop-website/
├── public/               # Static files
├── src/
│   ├── components/       # React components
│   ├── pages/           # Page components
│   ├── services/        # API calls
│   ├── styles/          # CSS files
│   ├── utils/           # Utility functions
│   └── App.js           # Main App component
├── server/              # Backend files (Node.js)
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   ├── controllers/      # Route controllers
│   └── config/          # Configuration files
├── .env.example         # Example environment variables
├── package.json         # Dependencies
└── README.md            # This file
```

## 🔌 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - Login user
- `POST /api/auth/logout` - Logout user

### Products
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get product details
- `GET /api/products/category/:category` - Get products by category

### Cart
- `POST /api/cart` - Add item to cart
- `GET /api/cart` - Get cart items
- `PUT /api/cart/:id` - Update cart item
- `DELETE /api/cart/:id` - Remove from cart

### Orders
- `POST /api/orders` - Create order
- `GET /api/orders` - Get user orders
- `GET /api/orders/:id` - Get order details

## 🤝 Contributing

Contributions are welcome! Here's how to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- **Author**: Ganeshyadav77
- **Email**: gy6606363@gmail.com
- **GitHub**: [Ganeshyadav77](https://github.com/Ganeshyadav77)

---

Made with ❤️ by Ganeshyadav77

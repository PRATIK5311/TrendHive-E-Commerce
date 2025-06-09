# TrendHive

> **Live Project**: [https://trendhive-frontend.vercel.app](https://trendhive-frontend.vercel.app)

TrendHive is a full-stack e-commerce platform built with modern technologies including **React**, **Express.js**, and **MongoDB**. Designed for performance, scalability, and an engaging user experience, TrendHive delivers a seamless shopping experience across devices.

---

## 🚀 Tech Stack

### Frontend:
- React (Hooks, Context API)
- React Router DOM
- Axios
- Tailwind CSS / CSS Modules
- React Toast Notifications

### Backend:
- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose
- JWT Authentication

### Deployment:
- Frontend: Vercel
- Backend: Render / Vercel Serverless / Railway (configurable)

---

## 🎯 Core Features

- 🔐 JWT-based Authentication (Login / Signup / Protected Routes)
- 🛒 Product Listing with Search, Filters, and Sorting
- 📦 Cart and Checkout Flow (COD / Future Stripe Integration)
- 👤 User Profile with Order History
- 🧑‍💼 Admin Panel (Product & Order Management)
- 📱 Mobile Responsive

---

## 🏗️ Project Structure (Frontend)

```
├── public/
├── src/
│   ├── api/              # Axios API handlers
│   ├── assets/           # Static images & icons
│   ├── components/       # Reusable UI components
│   ├── context/          # Global state management
│   ├── hooks/            # Custom React hooks
│   ├── pages/            # Page-level components (Home, Cart, etc)
│   ├── routes/           # Route definitions
│   ├── styles/           # Global styles
│   ├── App.jsx
│   └── main.jsx
```

---

## ⚙️ Getting Started

### Prerequisites

- Node.js >= 14
- MongoDB Atlas account

### Installation

```bash
git clone https://github.com/<your-username>/trendhive.git
cd trendhive
npm install
```

### Environment Setup

Create a `.env` file:

```env
REACT_APP_API_URL=https://your-api-domain/api
```

For backend:
```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
```

---

## 🧪 Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build
```

---

## 📡 API Structure (Simplified)

- `POST /auth/register` - Register user
- `POST /auth/login` - Authenticate user
- `GET /products` - Fetch product list
- `POST /cart` - Add to cart
- `POST /order` - Place order

---

## 🔮 Future Enhancements

- Stripe/Razorpay integration for online payments
- Wishlist & Reviews system
- Multi-vendor support
- Progressive Web App (PWA) support
- Dockerized deployment

---

## 🤝 Contributing

1. Fork the repo
2. Create a feature branch: `git checkout -b feature/<feature-name>`
3. Commit your changes
4. Open a pull request

---

## 📜 License

This project is open-source and available under the [MIT License](./LICENSE).

---

> Built and maintained with passion by [Your Name].

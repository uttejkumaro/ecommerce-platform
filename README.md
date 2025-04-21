

---

```markdown
<h1 align="center">🛒 MeshCommerce - Full-Stack E-Commerce Store</h1>

<p align="center">
  A fast, secure, and modern e-commerce web application built using Node.js, MongoDB, Redis, Stripe, Cloudinary, and Tailwind CSS.
</p>

---

## 🚀 Features Covered in This Project

- 🛠️ **Full Project Setup**
- 🗄️ **MongoDB** for storing products, users, coupons, and orders
- ⚡ **Redis (Upstash)** for caching featured products and storing refresh tokens
- 💳 **Stripe Integration** for secure payment processing
- 🔐 **JWT-Based Authentication** with Access & Refresh Tokens
- 👤 User Signup, Login, and Logout functionalities
- 🛍️ Add to Cart, Remove, and Update Quantity
- 📦 Product and Category Management
- 🏷️ Coupon System to apply discounts
- 👑 Admin Dashboard with analytics and controls
- 📊 Daily Sales & Revenue Analytics
- 🎨 Responsive UI with Tailwind CSS
- 🔒 Secure Routes with Role-Based Protection
- 🧠 Smart Caching using Redis for better performance
- ⚙️ RESTful APIs using Express
- 🔍 Lean Mongo Queries for faster response

---

## 🧪 Tech Stack

- **Backend:** Node.js, Express
- **Database:** MongoDB (with Mongoose)
- **Caching & Token Storage:** Redis (via Upstash)
- **Authentication:** JWT (Access & Refresh Tokens)
- **Payments:** Stripe
- **Image Storage:** Cloudinary
- **Frontend Requests:** Axios
- **Styling:** Tailwind CSS

---

## 🔧 Environment Variables

Create a `.env` file in your root directory and configure it as shown:

```env
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

---

## 🛠️ Getting Started Locally

### 1. Build the app
```bash
npm run build
```

### 2. Start the development server
```bash
npm start
```

---

# 🛍️ E-Commerce Website W

A **full-stack, responsive e-commerce platform** built with the **MERN stack (MongoDB, Express.js, React.js, Node.js)**, featuring secure payments, an admin dashboard, and optimized APIs for scalability.  

---

## 🚀 Features

- 🌐 **Responsive UI** – Optimized for mobile, tablet, and desktop using **Tailwind CSS**  
- 🛒 **Product Management** – Add, edit, and delete products with real-time updates  
- 👤 **User Authentication** – Secure login/signup using JWT-based authentication  
- 🛍️ **Shopping Cart & Orders** – Smooth cart management and order tracking  
- 💳 **Payments Integration** – Supports **Stripe** and **Razorpay** for seamless checkout  
- 📦 **Inventory Management** – Auto-updates stock after every purchase  
- ⚡ **Scalability** – Optimized APIs to handle **3x concurrent users** during peak traffic  
- 🔑 **Admin Dashboard** – Manage products, users, and orders in a single place  
- 🧪 **API Testing** – Fully tested with **Postman**  

---

## 🛠️ Tech Stack

| Category          | Technologies Used                     |
|-------------------|-------------------------------------|
| Frontend          | React.js, Tailwind CSS              |
| Backend           | Node.js, Express.js                 |
| Database          | MongoDB (Mongoose)                  |
| Authentication    | JWT, bcrypt.js                      |
| Payments          | Stripe, Razorpay                    |
| API Testing       | Postman                             |
| Deployment        | Vercel / Netlify / Render / AWS     |

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/ecommerce-website.git
cd ecommerce-website

# Install dependencies for frontend and backend
cd frontend && npm install
cd ../backend && npm install

# Create a .env file in /backend with the following:
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STRIPE_SECRET=your_stripe_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret



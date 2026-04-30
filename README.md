# 🛒 ShopEase - Full E-Commerce Web Application

A full-stack e-commerce web application that supports both **Buyer** and **Vendor** functionalities.  
The platform allows users to browse products, manage carts, place orders, and enables vendors to manage their business and products efficiently.

---

## 🚀 Live Demo
👉 https://your-project-name.onrender.com  

---

## 💻 Local Setup
👉 http://localhost:3000

---

## 🎯 Objective

The objective of this project is to build a complete e-commerce system that:
- Connects buyers with vendors
- Provides a seamless shopping experience
- Demonstrates full-stack development concepts

---

## ✨ Features

### 👤 Buyer
- User Registration & Login  
- Browse & Search Products  
- Add to Cart & Manage Quantity  
- Checkout with Shipping Address  
- Payment Options (COD / UPI / Card)  
- Order History & Cancel Orders  

---

### 🏪 Vendor
- Vendor Registration & Login  
- Business Profile Management  
- Add / Edit / Delete Products  
- Stock Management  
- View Customer Orders  
- Update Order Status  
- Revenue Dashboard  

---

## ⚙️ Tech Stack

| Layer | Technology |
|------|-----------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose) |
| Authentication | express-session |
| Deployment | Render |
| Cloud Database | MongoDB Atlas |

---

## 🛠️ Setup & Installation

### Prerequisites
- Node.js (v16+)  
- MongoDB (Local or Atlas)  

---

📁 Project Structure

ecommerce/
├── server.js
├── .env
├── models/
│   ├── User.js
│   ├── Business.js
│   ├── Product.js
│   ├── Cart.js
│   └── Order.js
├── routes/
│   ├── authRoutes.js
│   ├── businessRoutes.js
│   ├── productRoutes.js
│   ├── cartRoutes.js
│   └── orderRoutes.js
├── middleware/
│   └── auth.js
└── public/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── app.js
    └── pages/
        ├── index.html
        ├── login.html
        ├── register.html
        ├── products.html
        ├── cart.html
        ├── checkout.html
        ├── orders.html
        └── vendor.html

---

### Steps to Run Locally

```bash
# Clone repository
git clone https://github.com/your-username/your-repo.git

# Navigate into project
cd ecommerce

# Install dependencies
npm install

# Create .env file and add:
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key

# Start server
npm start

# OR (development mode)
npm run dev


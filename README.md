# 🛒 ShopEase - Full E-Commerce Web Application

A full-stack e-commerce web application that supports both **Buyer** and **Vendor** functionalities, allowing users to browse products, manage orders, and handle business operations efficiently.

---

## 🚀 Live Demo
👉 https://local-business-directory-and-product.onrender.com/products

---

## ✨ Features

### 👤 Buyer
- Register/Login as Buyer  
- Browse and search products  
- Add products to cart and manage quantities  
- Checkout with shipping details  
- Select payment methods (COD / UPI / Card)  
- View order history and cancel orders  

---

### 🏪 Vendor
- Register/Login as Vendor  
- Create and manage business profile  
- Add, edit, and delete products  
- Manage product stock  
- View customer orders  
- Update order status (Pending → Confirmed → Shipped → Delivered)  
- Dashboard with revenue insights  

---

## ⚙️ Tech Stack

- Frontend: HTML, CSS, JavaScript  
- Backend: Node.js, Express.js  
- Database: MongoDB (Mongoose)  
- Authentication: express-session  
- Deployment: Render  
- Database Hosting: MongoDB Atlas  

---

## 🛠️ Setup & Installation

### Prerequisites
- Node.js (v16 or higher)  
- MongoDB (Local or Atlas)  

---

## 📁 Project Structure


ecommerce/
├── server.js
├── .env
├── models/
│ ├── User.js
│ ├── Business.js
│ ├── Product.js
│ ├── Cart.js
│ └── Order.js
├── routes/
│ ├── authRoutes.js
│ ├── businessRoutes.js
│ ├── productRoutes.js
│ ├── cartRoutes.js
│ └── orderRoutes.js
├── middleware/
│ └── auth.js
└── public/
├── css/
├── js/
└── pages/

---

### Steps

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo.git

# Navigate to project folder
cd ecommerce

# Install dependencies
npm install

# Create a .env file and add:
MONGODB_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key

# Start the server
npm start

# OR (for development)
npm run dev



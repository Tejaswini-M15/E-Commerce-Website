# 🛍️ E-Commerce Website (Shopping Cart System)
A full-stack **E-Commerce Website** built using **Java (Spring Boot) for the backend** and **React.js for the frontend**. The system allows users to **register, browse products, add them to the cart, and place orders with secure authentication**.

---

## 📌 Technologies Used
### Backend (Spring Boot & Hibernate)
- ☕ **Java**
- 🚀 **Spring Boot**
- 🗄 **Hibernate (JPA)**
- 🛢 **MySQL Database**
- 🔐 **Spring Security (JWT for authentication)**

### Frontend (React.js & Bootstrap)
- ⚛️ **React.js**
- 🔀 **React Router**
- 📡 **Axios (for API calls)**
- 🎨 **Bootstrap (for UI styling)**

---

## 📂 Folder Structure
📂 E-Commerce-Website/ │── 📂 backend/ # Spring Boot Backend │ ├── src/ │ ├── pom.xml │ ├── application.properties │── 📂 frontend/ # React Frontend │ ├── src/ │ ├── package.json │ ├── index.js │── 📜 README.md # Project Documentation



---

## 🔧 Setup & Installation
### 1️⃣ Backend (Spring Boot) Setup
#### 1. Clone the repository and navigate to the **backend** folder.
   cd backend
#### 2. Configure the database connection in application.properties.
#### 3. Build and run the backend using Maven.
   mvn clean install
   mvn spring-boot:run
#### 4. The backend will start on http://localhost:8080.
   
### 2️⃣ Frontend (React.js) Setup
#### 1. Navigate to the frontend folder.
   cd frontend
#### 2. Install dependencies.
   npm install
#### 3. Start the React app.
   npm start
#### 4. The frontend will start on http://localhost:3000.

📡 API Endpoints
🔑 Authentication APIs
POST /api/auth/register → Register a new user
POST /api/auth/login → Login and get JWT token
🛍️ Product APIs
GET /api/products → Fetch all products
POST /api/products/add → Add a new product (Admin only)
🛒 Cart & Order APIs
POST /api/cart/add → Add item to cart
POST /api/orders/place → Place an order
🚀 Future Enhancements
⭐ Wishlist feature
🤖 AI-based product recommendations
📦 Enhanced order tracking
🤝 Contributing
💡 Feel free to fork this repository and submit pull requests!

This project is maintained by Tejaswini Mohapatra & Team. 🚀

# 🛍️ E-Commerce Website (Shopping Cart System)
A full-stack **E-Commerce Website** built using **Java (Spring Boot) for the backend** and **React.js for the frontend**. This system allows users to **register, browse products, add them to the cart, and place orders securely with authentication**.

---

## 📌 Technologies Used

### 🔹 Backend (Spring Boot & Hibernate)
- ☕ **Java**
- 🚀 **Spring Boot**
- 🗄 **Hibernate (JPA)**
- 🛢 **MySQL Database**
- 🔐 **Spring Security (JWT for authentication)**
- 🌐 **RESTful APIs**

### 🔹 Frontend (React.js & Bootstrap)
- ⚛️ **React.js**
- 🔀 **React Router**
- 📡 **Axios (for API calls)**
- 🎨 **Bootstrap (for UI styling)**

---

## 📂 Project Structure

```
E-Commerce-Website/
│── backend/                 # Spring Boot Backend
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/ecommerce/  # Java source files
│   │   │   ├── resources/
│   │   │       ├── application.properties  # Configuration file
│   │   ├── test/
│   ├── pom.xml              # Maven build file
│   ├── README.md
│
│── frontend/                # React Frontend
│   ├── src/
│   │   ├── components/      # UI Components
│   │   ├── pages/           # Page-specific components
│   │   ├── services/        # API calls (Axios)
│   │   ├── App.js           # Main React App
│   ├── public/
│   ├── package.json         # Dependencies & scripts
│   ├── README.md
│
│── README.md                # Project Documentation
```

---

## 🔧 Setup & Installation

### 🛠 Backend (Spring Boot) Setup
1. Clone the repository and navigate to the **backend** folder.
   ```sh
   cd backend
   ```
2. Configure the database connection in `application.properties`.
3. Build and run the backend using Maven:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```
4. The backend will start at **http://localhost:8080**.

### 🎨 Frontend (React.js) Setup
1. Navigate to the **frontend** folder.
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React app:
   ```sh
   npm start
   ```
4. The frontend will start at **http://localhost:3000**.

---

## 📡 API Endpoints

### 🔑 Authentication APIs
- **POST** `/api/auth/register` → Register a new user
- **POST** `/api/auth/login` → Login and receive a JWT token

### 🛍️ Product APIs
- **GET** `/api/products` → Fetch all products
- **POST** `/api/products/add` → Add a new product (Admin only)

### 🛒 Cart & Order APIs
- **POST** `/api/cart/add` → Add item to cart
- **POST** `/api/orders/place` → Place an order

---

## 🚀 Future Enhancements
- ⭐ Wishlist feature
- 🤖 AI-based product recommendations
- 📦 Enhanced order tracking
- 📊 Admin dashboard for analytics

---

## 🤝 Contributing
💡 Feel free to fork this repository and submit pull requests!

---

## 👥 Team Members
- **Tejaswini Mohapatra** 
- **Md Sharique Raza**
- **Harsh Verma**
- **Nishant Kumar** 🚀


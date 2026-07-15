# 📚 BookStore – MERN Stack Online Book Store

A full-stack online bookstore built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to browse books, search by title or category, add books to the cart, and securely authenticate. Admins and sellers can manage books and orders through dedicated dashboards.

---

## 🚀 Features

### 👤 User
- User Registration & Login
- JWT Authentication
- Browse Books
- Search Books
- Filter by Category
- View Book Details
- Add to Cart
- Responsive UI

### 🛒 Seller
- Seller Login
- Add New Books
- Update Book Details
- Delete Books
- Manage Inventory

### 👨‍💼 Admin
- Admin Login
- Manage Users
- Manage Sellers
- Manage Books
- Dashboard with Statistics

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- React Router DOM
- Axios
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt.js
- Multer
- CORS

---

## 📂 Project Structure

```
BookStore/
│
├── client/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── server.js
│   ├── package.json
│   └── .env
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/bookstore.git
```

### Backend Setup

```bash
cd server
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run the backend:

```bash
npm start
```

or

```bash
node server.js
```

---

### Frontend Setup

```bash
cd client
npm install
```

Install required packages:

```bash
npm install react-router-dom axios
```

Run frontend:

```bash
npm run dev
```

---

## 📌 API Endpoints

### Authentication

```
POST /api/users/register
POST /api/users/login
```

### Books

```
GET /api/books
GET /api/books/:id
POST /api/books
PUT /api/books/:id
DELETE /api/books/:id
```

### Cart

```
GET /api/cart
POST /api/cart
DELETE /api/cart/:id
```

---

## 📸 Screens

- Home Page
- Login
- Register
- Book Details
- Cart
- Seller Dashboard
- Admin Dashboard

---

## 🔐 Authentication

- JSON Web Token (JWT)
- Protected Routes
- Password Encryption using Bcrypt

---

## 🌟 Future Enhancements

- Online Payment Integration
- Wishlist
- Book Reviews & Ratings
- Order Tracking
- Email Notifications
- Dark Mode
- AI Book Recommendation

---

## 👩‍💻 Author

**Sneha**

Final Year B.Tech (CSE)

Aspiring AI/ML Engineer & Software Developer

---

## 📄 License

This project is created for educational and learning purposes.

# 📚 Book Store — MERN Stack

A full-stack Book Store application built with the MERN stack (MongoDB, Express.js, React, Node.js). Supports complete CRUD operations with a clean, responsive UI built using React, Vite, and Tailwind CSS.

---

## 🚀 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React, Vite, Tailwind CSS, React Router DOM |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas, Mongoose |

---

## ✨ Features

- 📖 View all books in a list or card layout
- 🔍 View detailed information for a single book
- ➕ Add a new book via a modal form
- ✏️ Edit existing book details
- 🗑️ Delete a book with confirmation
- 🔔 Real-time UX alerts for user feedback
- 🔒 CORS-configured backend for secure API access

---

## 📁 Project Structure

```
book-store-mern/
├── backend/
│   ├── models/
│   │   └── bookModel.js
│   ├── routes/
│   │   └── booksRoute.js
│   ├── config.js
│   └── index.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── BookCard.jsx
│   │   │   ├── BookModal.jsx
│   │   │   └── Spinner.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── ShowBook.jsx
│   │   │   ├── CreateBook.jsx
│   │   │   ├── EditBook.jsx
│   │   │   └── DeleteBook.jsx
│   │   └── App.jsx
│   └── index.html
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

- Node.js v18+
- MongoDB Atlas account
- npm or yarn

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Book-Store-MERN-Stack.git
cd Book-Store-MERN-Stack
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file in the `backend/` directory:

```env
MONGODB_URI=mongodb+srv://<username>:<password>@your-cluster.mongodb.net/books-store?retryWrites=true&w=majority
PORT=5555
```

Start the backend server:

```bash
npm run dev
```

### 3. Frontend Setup

```bash
cd ../frontend
npm install
npm run dev
```

The frontend runs at `http://localhost:5173` and the backend at `http://localhost:5555`.

---

## 🌐 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/books` | Get all books |
| GET | `/books/:id` | Get a single book |
| POST | `/books` | Create a new book |
| PUT | `/books/:id` | Update a book |
| DELETE | `/books/:id` | Delete a book |

---
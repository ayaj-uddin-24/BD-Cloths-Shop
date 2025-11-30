# BD Cloths Shop

### A Complete Full-Stack E-Commerce Website Built with the MERN Stack

[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react)](https://reactjs.org/) [![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?logo=node.js)](https://nodejs.org/) [![MongoDB](https://img.shields.io/badge/MongoDB-7.x-47A248?logo=mongodb)](https://www.mongodb.com/)

## Deployment

- Frontend Live Demo → https://bd-cloths-shop.onrender.com
- Admin Live Demo → https://admin-panel-bd-cloths-shop.onrender.com
- Backend URL → https://bd-cloths-shop-backend.onrender.com

## Features

- Complete user authentication (Register, Login, Logout, Protected Routes)
- Product browsing with category, price, and search filters
- Add to cart functionality
- Secure checkout process with order history
- Admin dashboard (add/edit/delete products)
- Responsive design – works perfectly on mobile, tablet, and desktop
- JWT-based authentication + password hashing with bcrypt
- Cloudinary image upload for products
- Pagination & search on both client and admin panels

## Tech Stack

### Frontend

- React 18 + Vite
- React Router DOM v6
- Redux Toolkit + RTK Query (state & data fetching)
- Tailwind CSS / DaisyUI (or your chosen styling solution)
- React Toastify for notifications
- Axios for API calls

### Backend

- Node.js + Express.js
- MongoDB with Mongoose ODM
- JWT for authentication
- bcrypt for password hashing
- Cloudinary for image storage
- CORS & helmet for security

### Tools & Others

- Git & GitHub
- Postman (API testing)
- Vercel / Render / Railway (deployment)

## Project Structure

```
bd-cloths-shop/
|
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── context/
│       ├── pages/
│       ├── App.jsx
│       └── index.jsx
|
├── admin/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── App.jsx/
│       ├── index.jsx
│
├── backend/
│   ├── index.js
│   └── uploads
│
└── README.md
```

## Quick Start (Local Development)

### Prerequisites

- Node.js ≥ 18
- MongoDB (local or MongoDB Atlas)
- Cloudinary account

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/ayaj-uddin-24/bd-cloths-shop.git
   cd bd-cloths-shop
   ```

2. **Backend Setup**

   ```bash
   cd backend
   npm install
   # Edit .env with your MongoDB URI, Cloudinary credentials, JWT secret
   npm start
   ```

   Server runs on http://localhost:5000

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```
   Frontend runs on http://localhost:5173

4. **Admin Setup**
   ```bash
   cd admin
   npm install
   npm run dev
   ```
   Admin runs on http://localhost:5174

## Deployment

- Frontend → Vercel / Netlify
- Backend → Render / Railway / Cyclic
- Database → MongoDB Atlas

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## Contact & Support

- GitHub: [@ayaj-uddin-24](https://github.com/ayaj-uddin-24)
- Email: ayajuddin2024@gmail.com

---

**- Created By Ayaj Uddin Tanif (MERN Stack Web Developer)**

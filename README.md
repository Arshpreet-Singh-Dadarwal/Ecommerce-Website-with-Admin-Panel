# 🛍️ Ecommerce Website with Admin Panel

This is a **full-stack Ecommerce Web Application** built using **Node.js**, **Express.js**, and **EJS** templating. The project includes a user-facing storefront where customers can browse products and place orders, as well as an **Admin Panel** where admins can manage products, users, and orders.

---

## 🚀 Features

### 🧑‍💻 User Features
- Browse all products
- View product details
- User registration and login
- Authenticated users can place orders
- Simple cart & checkout UI

### ⚙️ Admin Panel Features
- Admin authentication (protected routes)
- Dashboard with analytics
- Add, edit, delete products
- Manage user accounts
- View & manage orders
- Order status updating

---

## 🧠 Tech Stack

- **Backend:** Node.js, Express.js  
- **Frontend:** EJS (server-side templating)  
- **Database:** MongoDB (or specify if using another DB)  
- **Session & Auth:** Express sessions  
- **File Uploads:** Multer (for product images)  
- **Routing:** Express Router

---

## 📁 Project Structure

```plaintext
Ecommerce-Website-with-Admin-Panel/
│── client/             # Frontend UI files
├── server/             # Backend code (Express)
├── public/             # Static files (CSS, JS, images)
├── views/              # EJS templates
├── routes/             # Express routes
├── models/             # Database models
├── controllers/        # Controller logic
├── uploads/            # Uploaded product images
├── .env                # Environment variables
├── app.js              # App entry point
├── package.json

1. Clone the repo
git clone https://github.com/Arshpreet-Singh-Dadarwal/Ecommerce-Website-with-Admin-Panel.git

2. Navigate into the folder
cd Ecommerce-Website-with-Admin-Panel

3. Install dependencies
npm install

4. Create .env file
Create a .env file in the root and add:
PORT=3000
DATABASE_URL=your_database_connection_string
SESSION_SECRET=your_session_secret

5. Start the server
npm start

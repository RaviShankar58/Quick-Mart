📦 Quick Mart - E-commerce App

Quick Mart is a full-featured e-commerce application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It offers users a seamless experience to browse, 
search, and purchase products online, along with an admin panel for product, user, and order management.

🚀 Features
👤 User Features

User Authentication: Secure sign up and log in for personalized experiences.

Product Browsing: Browse through categories of products and view product details.

Search Functionality: Search products by name, category, or other filters.

Shopping Cart: Add products to your cart and view/update cart contents.

Checkout Process: Easy and secure checkout with Stripe payment integration.

🛠️ Admin Features
Admin Authentication: Secure admin login to access the management dashboard.

Product Management: Add, update, or delete products listed on the platform.

User Management: View, edit, or delete user accounts.

Order Management: Track and manage customer orders, including marking them as shipped or completed.

📝 Technologies Used
Frontend: React.js (with hooks, context API, and React Router)

Backend: Node.js with Express.js

Database: MongoDB (running locally on development machine)

Authentication: JWT (JSON Web Token)

Payment Integration: Stripe API

Styling: Tailwind CSS

Version Control: Git & GitHub

🎯 Key Learnings
While developing Quick Mart, I strengthened my skills in:

Full-Stack Development with the MERN stack.

React Hooks and Context API for state management.

Secure user authentication and authorization using JWT.

Integrating a payment gateway (Stripe) with a Node.js backend.

Creating a dynamic admin dashboard for complete operations.

RESTful API design and consumption.

Environment variable management and local MongoDB database setup.

Using Tailwind CSS for building responsive and clean UIs.

Version control and collaborative workflow with Git.

Running frontend and backend concurrently using a single command for efficient development workflow.

📦 Installation
📋 Prerequisites
Node.js (version ≥ 14)

MongoDB installed locally

Stripe account (for payments)

🔧 Clone the Repository
bash
Copy
Edit
git clone https://github.com/RaviShankar58/Quick-Mart.git
cd quick-mart
📦 Install Dependencies (Both Frontend & Backend)
bash
Copy
Edit
npm install --prefix frontend
npm install --prefix backend

🚀 Running the Application
To run both backend and frontend concurrently:

bash
Copy
Edit
npm run dev

(Assuming you’ve configured a concurrent script in your package.json)

📱 Usage
Once both servers are running:

Browse products.

Add products to your cart.

Sign up and log in to make purchases.

Proceed to checkout with payment.

Use the Admin Dashboard to manage products, users, and orders.

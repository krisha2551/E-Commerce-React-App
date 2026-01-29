🛒 Urban-Cart – React E-Commerce App

Urban-Cart is a modern e-commerce web application built with React + Vite + Bootstrap.
It allows users to browse products, add items to the cart, place orders, and manage order history.

🖥️ Screenshots

🏪 Product Listing Page
<img width="1920" height="2647" alt="image" src="https://github.com/user-attachments/assets/c40b937d-6fab-4cf7-b1e0-35b3193e0530" />


🛍️ Add to Cart Popup

<img src="./public/assets/1.png" width="900" alt="" />


🛒 Cart Modal
<img width="1920" height="2647" alt="image" src="https://github.com/user-attachments/assets/9154884c-acc3-4ca6-87d0-f1e327cb38b2" />



📦 Orders Page
<img width="1920" height="1938" alt="image" src="https://github.com/user-attachments/assets/db8c8a6b-b3b2-481f-bc7c-caaca6751caa" />


🚀 Features

✅ Product Listing (Grid Layout)

✅ Add to Cart Functionality

✅ Cart Modal with Items & Total Price

✅ Place Order Feature

✅ Orders History (Completed / Pending)

✅ Update Order Status

✅ Delete Orders

✅ Loading & Error Handling

✅ Responsive UI with Bootstrap


🛠️ Tech Stack

⚛️ React (Vite)

🎨 Bootstrap 5

📦 JSON Server (Mock API)

🧠 React Hooks & Custom Hooks

💾 Local Storage

🧩 Modular Components

📂 Project Structure

src/
│── assets/
│── components/
│   ├── CartModal.jsx
│   ├── Error.jsx
│   ├── Loading.jsx
│   ├── Navbar.jsx
│   ├── Orders.jsx
│   ├── Product.jsx
│── hooks/
│   ├── http.js
│── App.jsx
│── main.jsx
│── index.css
│── db.json

⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/your-username/urban-cart.git

2️⃣ Install Dependencies
npm install

3️⃣ Start the React App
npm run dev

4️⃣ Start JSON Server (API)
npx json-server --watch db.json --port 5000

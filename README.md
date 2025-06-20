👗 Cloth Rental Website

A full-stack MERN website for renting clothes online. Users can sign up, log in, browse clothes, add items to their cart, and place orders. An admin panel is also included for managing product listings. Automated UI tests are provided using Selenium.

📁 Project Structure
cloth-rental-website/
├── frontend/ # React frontend for users
├── backend/ # Node.js + Express backend server
├── admin/ # Vite + React admin dashboard
├── selenium-tests/ # Selenium automated test scripts
├── .gitignore
└── README.md

🚀 How to Run the Project

1. Start the Backend Server

```bash
cd backend
npm install
node index.js
```
Make sure MongoDB is running on your system before this step.

2. Run the User Frontend

```bash
cd frontend
npm install
npm start
```
Runs the React frontend on http://localhost:3000

3. Run the Admin Panel

```bash
cd admin
npm install
npm run dev
```
Runs the Vite admin panel on http://localhost:5173

4. Run Selenium Tests (Optional)

```bash
cd selenium-tests
npm install
node test.js
```

💡 Features

🔐 User authentication (login/signup)
👚 Product listing for men, women, and kids
🛒 Add to cart & remove from cart functionality
💻 Admin dashboard for uploading new products
📸 Image upload & preview
🧪 Selenium-based automated testing
📦 REST API integration with MongoDB

🌐 Tech Stack

✅React.js (frontend)
✅Vite + React (admin)
✅Node.js + Express.js (backend)
✅MongoDB (database)
✅Multer (image uploads)
✅Selenium (testing)

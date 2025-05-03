A simple and functional e-commerce web application built using HTML, CSS, JavaScript for the frontend and Node.js, Express, MongoDB for the backend. The application supports user signup, login, product viewing, cart management, and order placement.

Tech Stack:
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: MongoDB (via Mongoose)
Other Packages: bcryptjs, cors, body-parser

How to Run the Project:

Clone the Repository
git clone https://github.com/your-username/creative-online-shop.git
cd creative-online-shop

Install Backend Dependencies
npm init -y
npm install express mongoose body-parser
npm install cors mongoose body-parser
npm install bcryptjs

Start the Server
node app.js

Make sure your MongoDB server is running locally on the default port (27017).
The backend server will run at: http://localhost:5000

Project Structure:

creative-online-shop/
├── backend/
│ └── user.js (Mongoose User schema)
├── public/
│ ├── index.html (Homepage with Sign In / Sign Up buttons)
│ ├── signup.html (User registration)
│ ├── login.html (User login)
│ ├── products.html (Product display)
│ ├── cart.html (Cart view)
│ └── order.html (Order placement page)
├── app.js (Main server file)
├── package.json (Project metadata and dependencies)
└── README.md (Project instructions and info)

Features:

User registration with encrypted passwords

User login authentication

Product listing and "Add to Cart" functionality

Cart summary and order confirmation

Full frontend-backend integration

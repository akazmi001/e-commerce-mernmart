E-Commerce MERN Mart
An online marketplace application with seller accounts, product search and suggestions, shopping cart, order management, payment processing with Stripe, and live auction using Socket.io — built using React, Node.js, Express, and MongoDB.

<img align="center" src="https://s3.amazonaws.com/mernbook/git+/marketplace.png" width="56%"> <img align="center" src="https://mernbook.s3.amazonaws.com/git+/marketplace-bidding.png" width="42%">

🌐 Live Demo

🔗 https://mern-mart-kres.onrender.com

📌 Features

User authentication with JWT

Seller and buyer roles

Product listing and browsing

Product search and recommendations

Shopping cart functionality

Order management

Stripe payment integration (test mode)

Real-time bidding using Socket.io

RESTful API architecture

🛠 Tech Stack

Frontend

React

Material-UI

React Router

Backend

Node.js

Express.js

MongoDB (Mongoose)

✅ Requirements

To run this project, you need:

Node.js (16.x or above recommended)

npm or Yarn

MongoDB (local or MongoDB Atlas)

Stripe test account (optional)

▶️ How to Run Locally

Ensure MongoDB is running

Clone the repository:

git clone https://github.com/akazmi001/MERNMart.git


Open terminal in the project folder

Install dependencies:

npm install


Run the application in development mode:

npm run development


Open in browser:

http://localhost:3000

⚙️ Configuration

Update the following file with your own credentials:

config/config.js


Set values for:

MongoDB URI

JWT Secret

Stripe keys (if used)


📁 Project Structure
MERNMart/
│
├── client/        # React frontend
├── server/        # Express backend
├── config/        # Environment & app configuration
├── package.json
└── README.md

👤 Maintained By

Mohammad Anas
GitHub: https://github.com/akazmi001

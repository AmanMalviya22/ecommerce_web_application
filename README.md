# E-commerce Web Application with Stripe Payment Gateway

An E-commerce web application that allows users to browse products, add items to their cart, and securely process payments using Stripe. This project is built with a modern web stack to provide a seamless shopping experience.

## Folder Structure

```bash
ecommerce-app/
│
├── backend/                 # Backend Node.js server
│   ├── controllers/         # Controllers for handling requests
│   ├── models/              # MongoDB models
│   ├── routes/              # API routes
│   ├── middlewares/         # Authentication and error handling
│   ├── config/              # Configuration for environment and Stripe
│   └── app.js               # Main server entry point
│
├── frontend/                # Frontend React application
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Pages like Home, Product, Cart, Checkout
│   │   ├── services/        # API calls and business logic
│   │   ├── App.js           # Main React app
│   │   └── index.js         # React entry point
│   ├── public/              # Static files
│   └── package.json         # Frontend dependencies
│
├── .env                     # Environment variables for Stripe keys and other secrets
├── README.md                # Project documentation
├── package.json             # Backend dependencies
└── server.js                # Entry point for backend server


## Project Setup

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- **Node.js** (version 14 or higher)
- **MongoDB** (ensure a local instance is running or use a cloud instance)
- **Stripe Account** (for API keys)

### Installation

#### 1. Clone the repository


git clone https://github.com/your-username/ecommerce-app.git
cd ecommerce-app


#### 2. Backend Setup

 Navigate to the backend folder:

 cd backend

Install dependencies:

  npm install

Create a .env file in the backend folder and add your environment variables:

    PORT=5000
    MONGO_URI=your_mongo_db_uri
    STRIPE_SECRET_KEY=your_stripe_secret_key


Start the backend server:

  npm start

#### 3. Frontend Setup
Navigate to the frontend folder:

   cd ../frontend

Install dependencies:

   npm install
Start the React development server:

npm start

Running the Application
Ensure both MongoDB and Stripe configurations are correctly set.
Run the backend server and React frontend.
Open your browser and navigate to http://localhost:3000 to view the application.




![image](https://user-images.githubusercontent.com/70088342/160780701-7bb38a57-76bd-49a2-a4ec-49f89c50a7c7.png)
![image](https://user-images.githubusercontent.com/70088342/160780206-9cfe7c0a-3d8e-4a20-a055-b12efebe6c30.png)
![image](https://user-images.githubusercontent.com/70088342/160780265-692d37ac-7209-4d53-957a-e94b37d123c0.png)
![image](https://user-images.githubusercontent.com/70088342/160780381-7c947640-422e-4729-abae-21911e9bc716.png)
![image](https://user-images.githubusercontent.com/70088342/160780549-111ed048-cd4b-4740-b2fd-2c6fc3520c52.png)
![image](https://user-images.githubusercontent.com/70088342/160780884-22d6025e-9b7d-4493-8136-b3dfbf00a32f.png)

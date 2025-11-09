MERN Personal Finance Dashboard

This repository contains a full-stack application for personal finance management. It provides a robust set of tools for users to monitor their income, track their expenditures, and plan their budgets. Built entirely with the MERN stack, the app offers a dynamic and responsive user experience for analyzing and understanding personal financial habits.

Key Features

Secure Authentication: A complete user registration and login system to ensure data privacy.

Financial Overview: A central dashboard that provides a high-level, consolidated view of your financial status.

Expense Logging: Functionality to log all expenditures, which can be sorted and filtered by category.

Income Tracking: Tools to log and manage multiple streams of income.

Budgeting Tool: A planning feature that allows users to create and manage monthly or categorical budgets.

Data Visualization: Interactive charts and graphs to help users identify spending trends and analyze their financial data visually.

Responsive Layout: A mobile-first design that adapts to all screen sizes, ensuring usability on desktops, tablets, and smartphones.

Tech Stack

This project is built using the following technologies:

MongoDB: A NoSQL database used as the primary data store for all user and transaction data.

Express.js: A minimal backend web framework for Node.js, used to build and manage the RESTful API.

React.js: A frontend JavaScript library for building the dynamic and interactive user interface.

Node.js: The server-side runtime environment that executes the backend logic.

Local Setup

To run this project on your local machine, follow these steps:

Clone this repository:

git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)


Navigate into the main project folder:

cd your-repo-name


Install backend dependencies (from the server directory):

cd server
npm install


Install frontend dependencies (from the client directory):

cd ../client
npm install


Create a .env file in the server directory. You will need to add your environment variables here, such as your MONGODB_URI connection string and a JWT_SECRET.

Once configured, run both the backend and frontend servers.

To start the backend (from /server): npm start

To start the frontend (from /client): npm start

How to Use

Once the application is running:

Register for a new user account or log in with existing credentials.

View the main dashboard for a summary of your finances.

Navigate to the "Income" and "Expenses" sections to add new transactions.

Use the "Budgets" feature to set spending limits.

Visit the "Analytics" page to see visual breakdowns of your financial data.


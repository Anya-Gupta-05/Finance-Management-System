# MERN Personal Finance Dashboard

This repository contains a full-stack application for personal finance management. It provides a robust set of tools for users to monitor their income, track their expenditures, and plan their budgets. Built entirely with the MERN stack, the app offers a dynamic and responsive user experience for analyzing and understanding personal financial habits.

## Key Features

* **Secure Authentication**: A complete user registration and login system to ensure data privacy.

* **Financial Overview**: A central dashboard that provides a high-level, consolidated view of your financial status.

* **Expense Logging**: Functionality to log all expenditures, which can be sorted and filtered by category.

* **Income Tracking**: Tools to log and manage multiple streams of income.

* **Budgeting Tool**: A planning feature that allows users to create and manage monthly or categorical budgets.

* **Data Visualization**: Interactive charts and graphs to help users identify spending trends and analyze their financial data visually.

* **Responsive Layout**: A mobile-first design that adapts to all screen sizes, ensuring usability on desktops, tablets, and smartphones.

## Tech Stack

This project is built using the following technologies:

* **MongoDB**: A NoSQL database used as the primary data store for all user and transaction data.

* **Express.js**: A minimal backend web framework for Node.js, used to build and manage the RESTful API.

* **React.js**: A frontend JavaScript library for building the dynamic and interactive user interface.

* **Node.js**: The server-side runtime environment that executes the backend logic.

## Local Setup

To run this project on your local machine, follow these steps:

1. Clone this repository:
  ```bash
git clone https://github.com/Anya-Gupta-05/Finance-Management-System.git
```
2. Navigate into the main project folder:
   ```bash
   cd Finance-Management-System
   ```
3. Install backend dependencies (from the "server" directory):
     ```bash
     cd server npm install
     ```
4. Install frontend dependencies (from the `client` directory):
```bash
cd ../client npm install
```


6. Create a `.env` file in the `server` directory. You will need to add your environment variables here, such as your `MONGODB_URI` connection string and a `JWT_SECRET`.

7. Once configured, run both the backend and frontend servers.

* To start the backend (from `/server`): `npm start`

* To start the frontend (from `/client`): `npm start`

## How to Use

Once the application is running:

1. Register for a new user account or log in with existing credentials.

2. View the main dashboard for a summary of your finances.

3. Navigate to the "Income" and "Expenses" sections to add new transactions.

4. Use the "Budgets" feature to set spending limits.

5. Visit the "Analytics" page to see visual breakdowns of your financial data.

## Contributing

Feedback and contributions are encouraged. If you'd like to contribute, please feel free to fork the repository, make your changes, and submit a pull request.
   

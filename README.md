# Expense Tracker

An Expense Tracker application built with a full-stack approach to manage personal or business expenses efficiently. The project includes functionalities for tracking, adding, editing, and deleting expenses, as well as generating insights into financial habits.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)

---

## Features
- **User Authentication**: Sign up and log in securely.
- **Expense Management**: Add, edit, delete, and categorize expenses.
- **Dashboard**: Visual representation of expenses via graphs and charts.
- **Search and Filter**: Search expenses by category, date, or amount.
- **Responsive Design**: Works seamlessly on all devices.

---

## Technologies Used
- **Frontend**: React.js, Bootstrap, Chart.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Version Control**: Git, GitHub

---

## Setup
1. **Clone the repository**:
   
     git clone https://github.com/Kpooja0823/Expense-Tracker.git
   
     cd Expense-Tracker
3. **Install dependencies** :
    For the backend:
    cd backend
   
    npm install
    For the frontend:

    cd frontend
    npm install
   
5. **Environment Variables**:
   Create a .env file in the backend directory with the following:
   
    PORT=5000
    MONGO_URI=your_mongo_database_connection_string
   
7.  **Start the application**:
    Backend:
    
    cd backend
    npm start
    
    Frontend:
    
    cd frontend
    npm start
Open your browser and navigate to http://localhost:3000 for the frontend and http://localhost:5000 for the backend API.

**Usage**
Register or log in to your account.
Add your expenses by specifying the amount, category, and date.
Use the dashboard to view a breakdown of your spending habits.
Filter expenses by date range or category for detailed insights.

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgments**
This project was inspired by the need for simple, effective personal finance management. Special thanks to the open-source community for their tools and resources.

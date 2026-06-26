# ERP System

A full-stack ERP (Enterprise Resource Planning) System developed to simplify and automate business operations. The application provides a centralized platform for managing employees, departments, attendance, payroll, inventory, and other organizational processes through a secure and user-friendly interface.

## Features

- Secure user authentication and authorization
- Role-based access control (Admin, Employee, Manager)
- Employee management
- Department management
- Attendance management
- Leave management
- Payroll management
- Dashboard with analytics
- CRUD operations for all modules
- Responsive user interface
- RESTful API architecture
- Database integration for persistent data storage

## Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend
- Node.js
- Express.js

### Database
- MongoDB

## Project Structure

```
ERP-SYSTEM/
│
├── client/                 # Frontend
├── server/                 # Backend
├── models/                 # Database models
├── routes/                 # API routes
├── controllers/            # Business logic
├── middleware/             # Authentication middleware
├── config/                 # Database configuration
├── public/
├── package.json
└── README.md
```

## Installation

### Clone the repository

```bash
git clone https://github.com/rajputranjan7/ERP-SYSTEM.git
```

### Navigate to the project

```bash
cd ERP-SYSTEM
```

### Install Backend Dependencies

```bash
cd server
npm install
```

### Install Frontend Dependencies

```bash
cd ../client
npm install
```

## Environment Variables

Create a `.env` file inside the server directory.

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Running the Project

### Start Backend

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm start
```

The application will run on:

Frontend

```
http://localhost:3000
```

Backend

```
http://localhost:5000
```

## API Modules

- Authentication
- Employee
- Department
- Attendance
- Leave
- Payroll
- User Management

## Security

- JWT Authentication
- Password Encryption
- Protected Routes
- Role-Based Authorization
- Input Validation

## Future Improvements

- Email Notifications
- Report Generation (PDF/Excel)
- Performance Dashboard
- Inventory Management
- Expense Tracking
- Multi-Branch Support
- Audit Logs
- Docker Deployment
- Cloud Deployment



## License

This project is licensed under the MIT License.

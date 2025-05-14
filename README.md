
# Employee CURD App - MEAN

A MEAN stack application with basic CURD (Create, Update, Read, Delete) operations to manage Employee details.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a simple CRUD application built using the MEAN (MongoDB, Express.js, Angular, Node.js) stack. It allows users to manage employee data by performing operations like creating, reading, updating, and deleting employee records.

## Features

- Add new employees
- View employee details
- Update employee information
- Delete employee records
- Responsive and user-friendly interface

## Technologies Used

- **Frontend**: Angular, HTML, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: RESTful API, JavaScript

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/zeeshank1/employee-curd-app-mean.git
   ```
2. Navigate to the project directory:
   ```bash
   cd employee-curd-app-mean
   ```
3. Install dependencies for the backend:
   ```bash
   npm install
   ```
4. Navigate to the Angular frontend directory:
   ```bash
   cd frontend
   npm install
   ```
5. Set up environment variables for the backend (e.g., MongoDB connection string).
6. Start the backend server:
   ```bash
   npm start
   ```
7. Start the Angular frontend:
   ```bash
   ng serve
   ```

## Usage

1. Open your browser and navigate to `http://localhost:4200`.
2. Use the interface to manage employee data:
   - Add a new employee
   - Edit existing employee information
   - View employee details
   - Delete an employee

## Folder Structure

The repository is structured as follows:

```
employee-curd-app-mean/
│
├── backend/            # Backend code (Node.js, Express.js)
│   ├── routes/         # API routes
│   ├── models/         # Database models
│   └── app.js          # Main server file
│
├── frontend/           # Frontend code (Angular)
│   ├── src/            # Angular source files
│   └── angular.json    # Angular configuration file
│
├── README.md           # Project documentation
└── package.json        # Project dependencies
```

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.



You can copy this into your `README.md` file. Let me know if you need any modifications!

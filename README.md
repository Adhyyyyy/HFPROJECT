# Hostel Finder DBMS Project

A comprehensive hostel management system with both client and admin interfaces, built using the MERN stack.

## Features

- User authentication and authorization
- Hostel management
- Room and bed management
- Booking system
- Restaurant management
- Review system
- Admin dashboard
- Responsive design

## Tech Stack

- **Frontend (Client & Admin)**: React.js, CSS/SCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT

## Project Structure

```
├── client/                 # Client-side React application
│   ├── src/
│   │   ├── components/     # Reusable components
│   │   ├── pages/         # Page components
│   │   ├── hooks/         # Custom hooks
│   │   └── styles/        # CSS styles
│
├── admin/                  # Admin-side React application
│   ├── src/
│   │   ├── components/    # Admin components
│   │   ├── pages/        # Admin pages
│   │   ├── context/      # React context
│   │   └── styles/       # Admin styles
│
└── api/                   # Backend API
    ├── controllers/       # Route controllers
    ├── models/           # MongoDB models
    ├── routes/           # API routes
    └── utils/            # Utility functions
```

## Setup Instructions

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd api
   npm install

   # Install client dependencies
   cd ../client
   npm install

   # Install admin dependencies
   cd ../admin
   npm install
   ```

3. Create a .env file in the api directory with the following variables:
   ```
   MONGO=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd api
   npm start

   # Start client server
   cd ../client
   npm start

   # Start admin server
   cd ../admin
   npm start
   ```

## Total Lines of Code

The project contains approximately 6,235 lines of code, distributed across:
- Client-side code
- Admin-side code
- Backend API
- Components
- Styles
- Utilities

## License

MIT 
# MERN Stack Tours & Travels Booking Website

A fully functional tours and travels booking platform built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) with a sleek, modern UI/UX design.

## Features

- **User Authentication**: Secure user registration, login, and sessions using JWT and cookies.
- **Tour Management**: Add, update, delete, and view tours.
- **Search Functionality**: Search tours by title, location, or price range.
- **Booking System**: Users can book tours easily.
- **Review System**: Users can add and view reviews for tours.
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices.
- **Modern UI/UX**: Elegant, user-friendly design for a seamless experience.

## Tools and Technologies

### Frontend:
- **React.js**: For building the user interface.
- **CSS Modules**: For styling individual components.
- **Axios**: For seamless API communication.

### Backend:
- **Node.js**: Server-side runtime environment.
- **Express.js**: Framework for building RESTful APIs.
- **MongoDB**: NoSQL database for storing user and tour data.
- **Mongoose**: For object data modeling (ODM).
- **JWT**: For secure authentication.
- **Bcrypt**: For password hashing.

## Getting Started

### Prerequisites
Make sure you have the following installed:
- **Node.js** (v14+)
- **MongoDB** (Atlas or local installation)
- **Git**

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/DasBytes/Travel-Booking-System.git
   ```

2. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```

3. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```

4. Set up the `.env` file in the backend folder with the following:
   ```env
   MONGO_URL=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. Start the backend server:
   ```bash
   cd ../backend
   npm run start-dev
   ```

6. Start the frontend server:
   ```bash
   cd ../frontend
   npm start
   ```



## Snapshots

### Homepage
Displays featured tours and an intuitive search functionality to explore available options.

### Tour Details Page
Shows a detailed view of a specific tour, including reviews and booking options.

## Contact

For any queries or feedback, feel free to reach out:

- **Email**: prantadas85463@gmail.com
- **GitHub**: [DasBytes](https://github.com/DasBytes/Travel-Booking-System.git)


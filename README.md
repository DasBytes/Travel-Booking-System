MERN Stack Tours & Travels Booking Website
A fully functional tours and travels booking platform built using the MERN stack (MongoDB, Express.js, React.js, and Node.js) with a modern UI/UX design.

Features
User Authentication: Register, login, and secure sessions using JWT and cookies.
Tour Management: Add, update, delete, and view tours.
Search Functionality: Search tours by title, location, or price range.
Booking System: Book tours
Review System: Users can add and view reviews for tours.
Responsive Design: Optimized for desktop, tablet, and mobile devices.
Modern UI/UX: Stylish design with seamless user experience.
Tools and Technologies
Frontend
React.js: For building the user interface.
CSS Modules: For styling the components.
Axios: For making API requests.
Backend
Node.js: Server-side runtime environment.
Express.js: Framework for building APIs.
MongoDB: Database for storing user and tour data.
Mongoose: For object data modeling.
JWT: For secure authentication.
Bcrypt: For password hashing.
Getting Started
Prerequisites
Ensure you have the following installed:

Node.js (v14+)
MongoDB ( Atlas)
Git
Installation
Clone the repository:

git clone https://github.com/your-username/mern-travel-booking.git

Install dependencies for the backend:

cd backend
npm install
Install dependencies for the frontend:

cd ../frontend
npm install
Set up the .env file in the backend folder:

MONGO_URL
JWT_SECRET=your_jwt_secret


Start the backend server:

cd ../backend
npm run start-dev
Start the frontend server:

cd ../frontend
npm start
Open your browser and navigate to:

http://localhost:3000
API Endpoints
User Authentication
POST /api/v1/auth/register: Register a new user.
POST /api/v1/auth/login: Login user.
Tours
POST /api/v1/tours: Create a new tour.
GET /api/v1/tours: Get all tours.
GET /api/v1/tours/:id: Get a single tour by ID.
PUT /api/v1/tours/:id: Update a tour.
DELETE /api/v1/tours/:id: Delete a tour.
Bookings
POST /api/v1/bookings: Create a new booking.
GET /api/v1/bookings: Get all bookings.
Reviews
POST /api/v1/reviews: Add a review.
GET /api/v1/reviews: Get all reviews.
Project Structure
mern-travel-booking/
|-- backend/
|   |-- controllers/
|   |-- models/
|   |-- routes/
|   |-- utils/
|   |-- .env
|   |-- index.js
|
|-- frontend/
|   |-- src/
|       |-- components/
|       |-- pages/
|       |-- App.js
|-- README.md
Snapshots
Homepage:

Displays featured tours and search functionality.
Tour Details Page:

Detailed view of a tour, including reviews and booking options.
Contact
For any queries or feedback, please reach out:

Email: prantadas85463@gamil.com
GitHub: https://github.com/DasBytes/Travel-Booking-System.git

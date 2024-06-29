
# Home Rental Booking System

A web application for managing home rentals, allowing users to list properties, book stays, and manage bookings.

## Features

- User registration and login
- Property listing and management
- Booking system with dynamic pricing
- User reviews and ratings
- Responsive design for mobile and desktop
- Secure authentication and session management

## Technologies Used

### Frontend
- **HTML5**: Structure and layout of web pages
- **CSS3**: Styling and design
- **JavaScript (ES6+)**: Interactive elements and functionality
- **Bootstrap**: Responsive design framework

### Backend
- **Node.js**: Server-side JavaScript runtime
- **Express.js**: Web framework for Node.js
- **MongoDB**: NoSQL database for storing application data
- **Mongoose**: Object Data Modeling (ODM) for MongoDB
- **EJS**: Templating engine for dynamic HTML rendering

### Additional Technologies
- **RESTful APIs**: For communication between frontend and backend
- **JSON**: Data format for API communication
- **Git**: Version control system
- **Postman**: API testing and development tool

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/homeRentals.git

Navigate to the project directory:
bash

cd home-rental-booking
Install dependencies:
bash

npm install
Set up your environment variables in a .env file:
bash

MONGODB_URI=your_mongodb_connection_string
PORT=your_preferred_port
SESSION_SECRET=your_session_secret
Usage
Start the server:
bash
npm start
Open your browser and visit http://localhost:your_port.
Project Structure
/models: Mongoose models for database schema
/routes: Express routes for handling requests
/views: EJS templates for dynamic content rendering
/public: Static files (CSS, JavaScript, images)
/controllers: Business logic for different routes

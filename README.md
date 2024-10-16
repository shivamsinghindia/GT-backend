

# Sports Booking Application - Backend

**Name**: Shivam Kumar Singh

**College ID Number**: IEC2021078

## Description
This is the backend part of the Sports Booking Application built using Node.js, Express, and MongoDB. The Sports Booking Application is a web-based platform designed to facilitate the booking of sports facilities. Users can easily find and reserve courts for various sports at different centers. The application provides a user-friendly interface for both users and administrators, allowing for efficient management of bookings, sports, and centers.

## Key Features
- User Registration and Authentication: Users can create accounts, log in, and manage their bookings securely using JWT (JSON Web Tokens) for authentication.
- Booking Management: Users can view available courts, select time slots, and make bookings. The application prevents double bookings by checking for existing reservations.

  

## Deployed Link
- [Backend Application](https://gt-backend.onrender.com/)


## Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- npm (Node Package Manager)

## Setup Instructions

1. **Clone the Repository**
   ```
   git clone https://github.com/shivamsinghindia/GT-backend.git
   cd backend
   ```
2. **Install Dependencies**
   ```
   npm install
   ```

4. **Create a `.env` File**
   Create a `.env` file in the root directory and add the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=4000
   ```

6. **Run the Application**
   ```
   npm start
   ```

8. **Open your API client (like Postman) and test the endpoints at** `http://localhost:4000/api`.

## Deployment Instructions
To deploy the backend application, we can use platforms like Render, Heroku, or DigitalOcean. Here I have used Render for deployment.


## Special Instructions
- Ensure that the CORS settings are configured to allow requests from the frontend application.
- Make sure to handle JWT tokens securely in your application.



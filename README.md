

```
# Sports Booking Application - Backend

**College ID Number**: [Your College ID Number Here]

## Deployed Link
- [Backend Application](https://gt-backend.onrender.com/)

## Description
This is the backend part of the Sports Booking Application built using Node.js, Express, and MongoDB. It provides RESTful APIs for managing sports centers, sports, bookings, and user authentication.

## Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- npm (Node Package Manager)

## Setup Instructions

1. **Clone the Repository**

   git clone https://github.com/yourusername/sports-booking-backend.git
   cd sports-booking-backend

2. **Install Dependencies**
   npm install

3. **Create a `.env` File**
   Create a `.env` file in the root directory and add the following variables:
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=4000

4. **Run the Application**
   npm start

5. **Open your API client (like Postman) and test the endpoints at** `http://localhost:4000/api`.

## Deployment Instructions
To deploy the backend application, you can use platforms like Render, Heroku, or DigitalOcean. Follow the respective platform's documentation for deployment instructions.

## Assumptions and Limitations
- The application assumes that MongoDB is properly set up and accessible.
- The application is designed for RESTful API consumption and may not include all edge cases.

## Special Instructions
- Ensure that the CORS settings are configured to allow requests from the frontend application.
- Make sure to handle JWT tokens securely in your application.

## Links
- [Deployed Backend](https://gt-backend.onrender.com/)
```


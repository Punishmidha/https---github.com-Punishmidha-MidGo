# MidGo - A Property Rental Platform  
### Full-Stack Web Application 🚀  

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Key Features](#key-features)
- [Setup Instructions](#setup-instructions)
- [Challenges Faced](#challenges-faced)
- [Acknowledgements](#acknowledgements)
- [Author Information](#author-information)
- [Project Links](#project-links)
- [Conclusion](#conclusion)

---

## Project Overview
**MidGo** is a full-stack web application designed for seamless property rental services. The platform allows users to create, browse, and book property listings. Property owners can easily manage their listings, while users can review and interact with listings securely. **MidGo** focuses on delivering essential features for property management, authentication, and bookings without integrating maps.

Built using **MongoDB**, **Express.js**, **Node.js**, and **EJS**, this application ensures a fast, scalable, and secure system for both users and property owners.

---

## Technologies Used

### Backend
- **MongoDB**: A NoSQL database for flexible data storage and management.
- **Express.js**: A Node.js framework for building web applications and APIs.
- **Node.js**: JavaScript runtime environment for executing server-side code.

### Authentication
- **Passport.js**: Middleware for user authentication with local strategies.
- **Dotenv**: Handles environment variables for security.

### Frontend
- **EJS**: Template engine to render dynamic HTML content.
- **Bootstrap**: CSS framework for responsive design.

### File Uploads
- **Multer**: Middleware for handling file uploads.

### Session Management
- **Express-Session**: For managing user sessions.
- **Connect Mongo**: Stores session data in MongoDB.

---

## Key Features
- **User Authentication**: Secure login and registration system using hashed passwords.
- **Property Listings**: Owners can create, update, and delete property listings.
- **Booking System**: Users can book properties, manage reservations, and review listings.
- **Review System**: Users can add reviews for properties they’ve booked.
- **File Uploads**: Supports image uploads for property listings using Multer.
- **Session Management**: Handles user sessions with MongoDB for data persistence.

---

## Setup Instructions

To set up **MidGo** locally, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/Punishmidha/midgo.git
    cd midgo
    ```

2. **Install Dependencies**:

    Run the following command to install all necessary dependencies:

    ```bash
    npm install
    ```

3. **Set Up Environment Variables**:

    Create a `.env` file in the root directory and add the following:

    ```bash
    # MongoDB
    ATLASDB_URL=your_mongodb_atlas_url

    # Session Secret
    SECRET=your_random_secret_key
    ```

4. **Run the Application**:

    Start the application with:

    ```bash
    node app.js
    ```

5. **Access the Application**:

    Open your browser and navigate to `http://localhost:3000` to explore **MidGo** locally.

---

## Challenges Faced

- **Session Management**: Implementing secure and persistent user sessions using MongoDB.
- **File Uploads**: Handling multiple file types and ensuring secure uploads using Multer.
- **Data Validation**: Ensuring input validation and sanitation across forms with libraries like Joi.

---

## Author Information
**Punish Midha**  
- LinkedIn: [Click here](https://www.linkedin.com/in/punish-midha-381777245/)
- GitHub: [Click here](https://github.com/Punishmidha)

---

## Project Links
- **Live Project**: [MidGo](https://https-github-com-punishmidha-midgo.onrender.com/)
- **GitHub Repository**: [MidGo Repo](https://github.com/Punishmidha/https---github.com-Punishmidha-MidGo)

---

## Conclusion
Thank you for exploring **MidGo**! If you have any feedback or suggestions, feel free to reach out. Your input is greatly appreciated.

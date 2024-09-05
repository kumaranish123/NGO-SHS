# NGO-SHS (Srijan Home School , Kurtha)


[Visit the website](https://srijanhomeschool.netlify.app/)

## Overview

Srijan Home School is a comprehensive platform designed to manage student performance, tests, announcements, and profiles. This full-stack web application is developed using the **React** library for the frontend and **MongoDB** for the backend. It provides a seamless user experience with features tailored for both students and administrators.

## Features

### General Features
- **Authentication System**: Users can register and log in with a secure authentication system.
- **Session Management**: Sessions are managed using session IDs stored in cookies, ensuring a secure and user-friendly experience.
- **School Information**: The homepage provides details about school admissions, available tests, faculty information, achievements, and more.

### Student Features
- **Test Taking**: Students can take tests directly on the platform.
- **Score Viewing**: After completing a test, students can view their scores.
- **Test Retake Option**: Students have the option to retake tests if needed.
- **PDF Downloads**: Authenticated students can download PDF versions of their question papers.

### Admin Features
- **Admin Login**: Admins can log in using a special admin ID.
- **Test Management**: Admins can add new tests, upload questions, and provide PDFs for the tests.
- **Announcement Management**: Admins can manage announcements related to the school or upcoming tests.

## Technology Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: Session-based authentication with session IDs stored in cookies

## Getting Started

### Prerequisites
- Node.js
- MongoDB

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/harshrajshs/srijan-home-school.git
   ```

2. Navigate to the project directory:
   ```bash
   cd srijan-hoome-school
   ```

3. Install the necessary dependencies for both frontend and backend:
   ```bash
   cd client
   npm install
   cd..
   cd server
   npm install
   ```

4. Set up environment variables:
   
    - Create a.env file in the root directory.
    -  Add your MongoDB URI, session secret, and any other required environment variables.

5. Start the clent:
   ```bash
   cd..
   cd client
   npm start
   ```
6. Start the Deveopement server:
   ```bash
   cd..
   cd server
   npm run dev
   ```

 7. Access the application in your browser at:
    ```bash
    http://localhost:3000
    ```

## Usage

   - Students: Register and log in to access tests and view scores.
   - Admins: Use your admin credentials to log in and manage tests, questions, and announcements.

## Future Improvements

   - Add role-based access control for different user levels.
   - Implement real-time notifications for new tests and announcements.
   - Enhance the user interface with more interactive elements.

## Contributing

   - If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

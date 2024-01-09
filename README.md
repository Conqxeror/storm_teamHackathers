# Employee Review System

## Overview
The Employee Review System is a web-based application that facilitates the process of employee performance reviews within an organization. It allows employees to provide feedback on their colleagues' performance, fostering a culture of constructive feedback and continuous improvement. The system supports both named and anonymous reviews, ensuring a flexible and inclusive approach to performance evaluation.

## Features

### 1. User Authentication
The system employs Passport.js and Passport-local for user authentication, ensuring secure access to the application. Employees can log in using their credentials, and the system supports local authentication.

### 2. Employee Reviews
Employees can submit reviews for their peers, managers, or team members. The review process includes a range of criteria, such as teamwork, communication, problem-solving, and more. Reviews can be submitted anonymously to encourage honest and unbiased feedback.

### 3. Anonymous Reviews
One of the key features of the Employee Review System is the ability to submit anonymous reviews. This ensures that employees feel comfortable providing candid feedback without fear of repercussions. The system uses Express-session for managing user sessions securely.

### 4. Data Storage
The application utilizes MongoDB as the database to store employee information, reviews, and user data. Connect-mongo is used for session storage, providing a persistent session store backed by MongoDB.

### 5. Flash Messages
Connect-flash is integrated into the system to display flash messages, providing feedback to users about the success or failure of their actions, such as successful login or errors during the review submission process.

### 6. Stylish UI with EJS and SASS
The frontend of the application is built using EJS templates and styled with SASS. Express-ejs-layouts helps in structuring and rendering the views seamlessly.

### 7. Real-time Feedback with Nodemon
Nodemon is used as a development dependency to ensure real-time updates during the development process. This facilitates a smooth development experience with automatic server restarts on code changes.

## Dependencies
- **body-parser:** Parse incoming request bodies in a middleware.
- **connect-flash:** Display flash messages to users.
- **connect-mongo:** Session store backed by MongoDB.
- **cookie-parser:** Parse Cookie header and populate req.cookies.
- **del:** Delete files and directories.
- **ejs:** Embedded JavaScript templating.
- **express:** Web application framework.
- **express-ejs-layouts:** Layout support for EJS.
- **express-session:** Simple session middleware for Express.
- **mongodb:** MongoDB driver for Node.js.
- **mongoose:** MongoDB object modeling tool.
- **node-sass-middleware:** Middleware that compiles Sass to CSS.
- **nodemon:** Automatically restart the server on code changes.
- **passport:** Authentication middleware for Node.js.
- **passport-local:** Passport strategy for authenticating with a username and password.
- **sass:** Syntactically awesome stylesheets.

## Getting Started
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Configure the MongoDB connection in the application.
4. Run the application using `npm start` or `nodemon`.

Feel free to customize and expand upon this Employee Review System to meet the specific needs and requirements of your organization. Happy coding!

# Jibber Jabber - Story Sharing Platform

A web application where users can share stories and interact with other users' content.

![image](https://github.com/user-attachments/assets/54f4db98-8613-4e89-950b-e80cddedea68)


## Features

- User authentication (signup, login, logout)
- Create, read, update, and delete stories
- User profiles with story management
- Rate limiting for login attempts
- Form validation and sanitization
- Flash messages for user feedback
- Responsive design

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Template Engine**: EJS
- **Authentication**: bcryptjs, express-session
- **Security**: express-validator, express-rate-limit
- **Other Tools**: 
  - connect-flash for flash messages
  - connect-mongo for session storage
  - morgan for logging
  - method-override for HTTP method override

## Installation

1. Clone the repository:
```bash
git clone https://github.com/mustafaap/JibberJabber-Story-Sharing-Platform.git
```

2. Install dependencies:
```bash
npm install
```

3. Make sure MongoDB is running locally on port 27017

4. Start the application:
```bash
nodemon run
```

5. Visit `http://localhost:3000` in your browser

## Environment Setup

Make sure you have:
- Node.js installed
- MongoDB installed and running
- Port 3000 available

## Project Structure

- `controllers/` - Route controllers
- `middlewares/` - Custom middleware functions
- `models/` - MongoDB schema models
- `public/` - Static files (CSS, images)
- `routes/` - Express routes
- `views/` - EJS templates
- `app.js` - Application entry point

## License

ISC License

## Author

Mustafa Poonawalla

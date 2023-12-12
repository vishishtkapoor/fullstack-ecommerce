# Twitter Clone - MERN Stack

## Overview

This project is a Twitter clone built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It replicates the core features of the popular social media platform Twitter, allowing users to post tweets, follow other users, and engage in real-time conversations.

## Features

- **User Authentication:** Users can sign up, log in, and log out securely. Passwords are hashed before storage.

- **Tweeting:** Users can compose and post tweets, including text and media attachments.

- **Following and Followers:** Users can follow and be followed by other users, enhancing the social aspect of the platform.

- **Real-time Updates:** The application utilizes WebSocket for real-time updates, ensuring users receive instant notifications about new tweets and interactions.

- **Responsive Design:** The user interface is designed to be responsive, providing a seamless experience across various devices.

## Technologies Used

- **Frontend:**
  - React.js
  - Redux for state management
  - Axios for HTTP requests
  - Socket.io-client for real-time communication

- **Backend:**
  - Node.js with Express.js
  - MongoDB for data storage
  - Mongoose as the ODM (Object Document Mapper)
  - WebSocket for real-time updates

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running
- Twitter API credentials (if any)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/twitter-clone.git
   cd twitter-clone
   ```

2. Install dependencies:

   ```bash
   cd client && npm install
   cd ../server && npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the `server` directory and set the following variables:
     - `MONGODB_URI`: MongoDB connection string
     - `JWT_SECRET`: Secret key for JWT token generation
     - `TWITTER_API_KEY`, `TWITTER_API_SECRET`, etc. (if Twitter API is used)

4. Start the development servers:

   ```bash
   # In the 'server' directory
   npm run dev

   # In the 'client' directory
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000` to access the Twitter clone.

## Acknowledgments

- Special thanks to the developers of the MERN stack and other open-source libraries used in this project.
The icons used are from [FontAwesome](https://fontawesome.com/).
-Also i would like to thank few creators from yt that help me build this.

## Contact

For inquiries or support, please contact [vishishtkapoor2@gmail.com].

Enjoy tweeting on your MERN stack Twitter clone! 🚀

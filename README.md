# Memories — Social Media Website

A full-stack social media web application where users can share, like, and manage their memorable posts.

## Features
- Create, update, and delete posts with image uploads
- Like posts from other users
- User authentication via email/password and Google OAuth (JWT-based sessions)
- Responsive UI built with React and Material UI

## Tech Stack
- **Frontend:** React, Redux, Material UI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Auth:** JWT, Google OAuth 2.0

## Getting Started

### Prerequisites
- Node.js v14+
- MongoDB (local or Atlas)

### Installation
```bash
# Clone the repo
git clone https://github.com/Tanishqua23/Memories-Social-Media-Website.git

# Install server dependencies
cd server && npm install

# Install client dependencies
cd ../client && npm install
```

### Running the App
```bash
# Start backend (from /server)
npm start

# Start frontend (from /client)
npm start
```

### Environment Variables
Create a `.env` file in `/server`:
```
CONNECTION_URL=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```


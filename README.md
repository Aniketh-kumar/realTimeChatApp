# Real Time Chat Application

A full-stack real-time chat application built with React, Redux, Node.js, Express, MongoDB, Socket.io, and Cloudinary.

## Features

- User authentication (Sign Up, Login, Logout)
- Real-time messaging with Socket.io
- Online users indicator
- Image upload support (Cloudinary)
- Emoji picker for messages
- Responsive UI with Tailwind CSS

## Technologies Used

- **Frontend:** React, Redux, React Router, Axios, Tailwind CSS, emoji-picker-react, socket.io-client
- **Backend:** Node.js, Express, MongoDB, Mongoose, bcryptjs, jsonwebtoken, multer, cloudinary, socket.io
- **Deployment:** MongoDB Atlas, Cloudinary

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB Atlas account
- Cloudinary account

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/Aniketh-kumar/realTimeChatApp.git
cd realTimeChatApp
```

#### 2. Backend Setup

```bash
cd backend
npm install
```

- Create a `.env` file in the `backend` folder and add your credentials:
  ```
  PORT=8000
  MONGODB_URL=your_mongodb_url
  JWT_SECRET=your_jwt_secret
  CLOUD_NAME=your_cloudinary_cloud_name
  API_KEY=your_cloudinary_api_key
  API_SECRET=your_cloudinary_api_secret
  ```

- Start the backend server:
  ```
  npm run dev
  ```

#### 3. Frontend Setup

```bash
cd ../frontend
npm install
```

- Start the frontend server:
  ```
  npm run dev
  ```

- Open [http://localhost:5173](http://localhost:5173) in your browser.

## Usage

- Register a new account or login.
- Start chatting with other online users.
- Send text, emojis, and images in real time.

## Folder Structure

```
chatapplication/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── config/
│   ├── .env
│   └── index.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── customHooks/
│   │   ├── main.jsx
│   │   └── App.jsx
│   └── package.json
└── README.md
```

## Environment Variables

See `.env` in the backend for required variables.

## License

This project is licensed under the MIT License.

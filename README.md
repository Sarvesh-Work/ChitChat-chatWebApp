# ChitChat - Real-Time Chat Web Application

**ChitChat** is a full-stack, real-time chat application built using the MERN stack, Socket.IO, Redux Toolkit, RTK Query, and React Hook Form. The application supports features like group messaging, real-time updates, and online/offline user status.

[📱 Visit ChitChat Project](https://chit-chat-chat-web-app.vercel.app/)

## ✨ Features

- Real-time messaging with **Socket.IO**
- Group chat functionality
- Online/offline status indicators
- Typing indicators
- Scalable architecture using **MERN stack**
- **JWT-based** authentication
- Responsive UI with **Material-UI**
- Efficient state management with **Redux Toolkit**
- API data fetching with **RTK Query**
- Form handling with **React Hook Form**

## 💻 Technologies

### Frontend (Client)
- **React** with functional components and hooks
- **Redux Toolkit** for state management
- **RTK Query** for API interactions
- **Material UI (MUI)** for the UI components
- **Socket.IO** for real-time communication
- **React Hook Form** for form handling

### Backend (Server)
- **Node.js** and **Express** for the server-side application
- **MongoDB** and **Mongoose** for database management
- **Socket.IO** for real-time WebSocket communication
- **JWT** for authentication

## 🔎 Glimpse of ChitChat

| ![Image 1](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495918/bxxw23ay0czvesexrizg.png) | ![Image 2](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495918/we4hogcsfdleewiya4so.png) |
|:----------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------:|
| ![Image 3](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495918/sysituvxmez8lgay9woo.png) | ![Image 4](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495917/ghjufffcyvbpzczuwqgh.png) |
| ![Image 5](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495917/ahqpw8qlbpvo9do2nxqk.png) | ![Image 6](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495917/lskry2dehwqzu6kp31tw.png) |
| ![Image 7](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495917/hhmzlcwxi2qt07iqgmvq.png) | ![Image 8](https://res.cloudinary.com/sarvesh-img/image/upload/v1726495917/qoqf5jarf7ncmrnkbxqj.png) |

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- **Node.js** (v14+)
- **MongoDB**
- **Git**

### Cloning

1. Clone the repository:

    ```bash
    git clone https://github.com/Sarvesh-Work/ChitChat-chatWebApp.git
    ```

2. Navigate to the project directory:

    ```bash
    cd ChitChat-chatWebApp
    ```

### Setting up the Client

1. Go to the **client** directory:

    ```bash
    cd client
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create an `.env` file in the `client` directory and add your environment variables.

4. Start the client application:

    ```bash
    npm start
    ```

### Setting up the Server

1. Go to the **server** directory:

    ```bash
    cd ../server
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create an `.env` file in the `server` directory and add the required environment variables:

    ```bash
    PORT=<Your server port (e.g., 5000)>
    MONGODB_URL=<Your MongoDB connection string>
    JWT_KEY=<Your JWT secret key>
    LIMIT_PER_PAGE=<Pagination limit per page (e.g., 20)>
    FRONTEND_PORT=<Your client app port (e.g., 3000)>
    CLOUD_NAME=<Your Cloudinary cloud name for image uploads>
    API_KEY=<Your Cloudinary API key>
    API_SECRET=<Your Cloudinary API secret>
    ```

4. Start the server:

    ```bash
    npm run dev
    ```



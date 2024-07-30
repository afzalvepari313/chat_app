# 💬 Full Stack Chat App with React, Socket.io, Node.js, Redux-Toolkit, MongoDB (2024)

![Alt text](Full%20Stack%20Chat%20App.png?raw=true "Title")

Learn to build a real-time messaging Chat App using React, Socket.io, Node.js, Redux-Toolkit, and MongoDB. This tutorial series covers everything from setup to implementation, offering valuable insights and practical skills. Whether you're a beginner or an experienced developer, join us to take your React and Node.js expertise to the next level! Subscribe now and start building your own real-time messaging platform.

## 📚 Table of Contents

- [Introduction](#-introduction)
- [Technologies](#-technologies)
- [Features](#-features)
- [Setup](#-setup)
  - [Server Environment Variables](#-server-environment-variables)
  - [Client Environment Variables](#-client-environment-variables)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)
- [Assets](#-assets)

## 🌟 Introduction

The Full Stack Chat App is a real-time messaging platform designed to provide users with a seamless chatting experience. It utilizes React for the frontend, Node.js and Socket.io for real-time communication on the backend, and MongoDB for data storage. Redux-Toolkit is used for state management on the frontend.

## 🛠 Technologies

This project is built using the following tools and technologies:

- **Frontend**: React, Redux-Toolkit
- **Backend**: Node.js, Express.js, Socket.io
- **Database**: MongoDB
- **Others**: Cloudinary for image uploads, JWT for authentication

## 🚀 Features

- User authentication and authorization
- Real-time messaging with Socket.io
- Profile creation and management
- Image upload and management
- Group chat functionality

## ⚙️ Setup

To set up the project locally, follow these steps:

### 🔧 Server Environment Variables

Create a `.env` file in the `server` directory and add your environment variables:

```env
FRONTEND_URL=<Frontend URL>
MONGODB_URI=<MongoDB URI>
JWT_SECRET_KEY=<JWT Secret Key>

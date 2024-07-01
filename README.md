# EstateApp Backend

## Introduction

An estate application using MERN stack integrated with Socket.IO for real-time communication, enhancing user interaction,
updates across property listings, client interactions and user notifications. User authentication with JWT.
1. MongoDB for data storage. Implementing RESTful APIs in Express.js for CRUD operations. Responsive frontend with
React.js for property listings and user dashboards.
2. This project aims to create a platform for real estate listings, where users can browse available properties, view details, and
contact agents or sellers. 


## Features

### Auth Management:

- Registration, login, logout
- Profile management (avatar, details)

### User Management:

- getUser, updateUser, daleteUser
- Save post, profile post
- get notification number
  
### Estate Management:

- Property publishing
- Get all posts, Get single post
- Update property
- Delete property

### Message Management:

### Chat Management:

- get chats, get chat
- add chat, read chat

### test

- should be logged in
- should be admin
  

## Technologies Used

- Node.js 
- Express.js
- MongoDB
- Cloudinary (must have an account)
- Socket.io (for communication)
- React.js (for frontend)

## Api Endpoints

1. **auth**
   ```bash
   /api/auth/register
   ```
   ```bash
   /api/auth/login
   ```
   ```bash
   /api/auth/logout
   ```
2. **users**
   ```bash
   /api/users/
   ```
   ```bash
   /api/users/:id
   ```
   ```bash
   /api/users/:id
   ```
   ```bash
   /api/users/profilePosts
   ```
   ```bash
   /api/users/notification
   ```
3. **posts**
   ```bash
   /api/posts/
   ```
   ```bash
   /api/posts/
   ```
   ```bash
   /api/posts/:id
   ```
   ```bash
   /api/posts/:id
   ```
   ```bash
   /api/posts/:id
   ```
4. **test**
   ```bash
   /api/test/should-be-logged-in
   ```
   ```bash
   /api/test/should-be-admin
   ```
5. **chats**
   ```bash
   /api/chats/
   ```
   ```bash
   /api/chats/
   ```
   ```bash
   /api/chats/:id
   ```
   ```bash
   /api/chats/read/:id
   ```
6. **messages**
   ```bash
   /api/messages/:chatId
   ```

## Installation and Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/2002nitesh/EstateApp.git
    ```

2. **Install dependencies:**

    ```bash
    cd api
    npm install
    ```

3. **Start the server:**

    ```bash
    npm run start
    ```

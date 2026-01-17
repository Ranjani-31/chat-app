# Instagram Clone – Full Stack MERN Application

A scalable, production-oriented Instagram-like social media platform built to demonstrate strong full-stack engineering skills, including authentication, real-time features, feed algorithms, performance optimization, and clean system design.

## 🚀 Project Overview

This project is not just a UI clone. It is a feature-complete social media system designed with real-world engineering principles such as secure authentication, optimized database queries, scalable feed generation, and real-time communication.

## 🧩 Tech Stack
- Frontend

- React.js

- React Router v6

- Custom Hooks

- Socket.io Client

## Backend

- Node.js

- Express.js

- MongoDB (Mongoose)

- JWT Authentication

- Socket.io

- Redis (Caching)

## DevOps & Tools

- Docker

- Nginx

- Cloudinary (Media storage)

- Postman (API Documentation)

- Git & GitHub

## 🔐 Authentication & Security

- Secure login & signup (JWT access + refresh tokens)

- Password hashing with bcrypt

- Protected routes (frontend & backend)

- Role-based authorization

- Input validation & sanitization

- Rate limiting & secure headers

## 👤 User Features

- User registration & login

- Profile creation & editing

- Profile picture & bio

- Public & private accounts

- Follow / unfollow users

- Follow request approval system

- Followers & following lists

## 📸 Post Features

- Image upload (Cloudinary)

- Multiple images per post (carousel)

- Captions & hashtags

- Like / unlike posts (idempotent APIs)

- Comment & reply system

- Edit & delete posts (ownership validation)

- Infinite scrolling feed

## 📰 Feed & Discovery

- Personalized user feed

- Feed ranking based on:

- Recency

- Engagement (likes & comments)

- Cursor-based pagination

- Explore feed (trending & non-followed posts)

- Hashtag-based discovery

## ⏱️ Stories

- 24-hour auto-expiring stories

- Story views tracking

- Viewer list

- Cron-based cleanup for expired stories

## 🔔 Real-Time Features

- Real-time notifications (Socket.io)

-  Notifications for:

  1. Likes

  2. Comments

  3. Follows

- Read / unread notification status

- Live comment updates

- 🔍 Search

- User search (username & name)

- Hashtag search

- Debounced search input

- Indexed MongoDB queries for performance

## 🛠️ Admin & Moderation

- Admin dashboard

- Reported posts management

- User suspension / banning

- Content removal

- Platform analytics (DAU, posts/day)

## ⚡ Performance Optimizations

- Redis caching for:

- Feed data

- User profiles

- MongoDB indexing strategy

- Optimized aggregation pipelines

- Lazy loading & skeleton screens

- Optimistic UI updates

## 🗂️ Database Design

- Main Collections:

  1. Users

  2. Posts

  3. Comments

  4. Likes

  5. Follows

  6. Notifications

  7. Stories

- Key Design Decisions:

  1. Prevent duplicate likes

  2. Soft deletes for critical data

  3. Efficient follower/following queries

  4. Indexed frequently accessed fields

## 📐 System Architecture

- RESTful API with versioning

- Event-driven notification system

- Real-time layer using WebSockets

- Modular backend architecture

- Feature-based frontend structure

## 📄 API Documentation

Postman UI available at:
/api/docs

## 🧪 Environment Variables
    Backend (.env)
    PORT=5000
    MONGO_URI=your_mongodb_url
    JWT_SECRET=your_jwt_secret
    JWT_REFRESH_SECRET=your_refresh_secret
    CLOUDINARY_NAME=your_cloudinary_name
    CLOUDINARY_API_KEY=your_key
    CLOUDINARY_API_SECRET=your_secret
    REDIS_URL=your_redis_url

## ▶️ Getting Started
    Clone the Repository
    git clone https://github.com/your-username/instagram-clone.git

## Install Dependencies
    cd backend
    npm install

    cd frontend
    npm install

## Run the Application
### # Backend
    npm run dev

### Frontend
    npm start

## 🐳 Docker Support
    docker-compose up --build

## 📌 Future Enhancements

- AI-based content recommendations

- Caption generation

- Image moderation (NSFW detection)

- Push notifications

- PWA offline support

- Multi-language support

## ⭐ Acknowledgements

**Inspired by modern social media platforms and built for learning, experimentation, and professional growth.**

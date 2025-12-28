# chat-app
## 💬 Real-Time Chat Application

A full-stack real-time communication platform supporting one-to-one chat, group chat, voice calls, video calls, and status updates, built with modern web technologies and scalable architecture principles.

## 📌 Overview

This project is a real-time chat application designed to replicate and understand the core architecture behind modern messaging platforms. It focuses on real-time systems, low-latency communication, secure authentication, and scalable backend design.

The application enables users to communicate seamlessly through text, voice, and video while maintaining performance, reliability, and security.

## 🚀 Features
- 🔐 Authentication & Security

- User registration and login

- JWT-based authentication

- Secure password hashing

- Protected routes and role-based access

## 💬 Messaging

- One-to-one real-time chat

- Group chat with admin controls

- Message delivery & read receipts

- Typing indicators

- Online/offline presence

- Message timestamps

- Soft delete messages

## 👥 Group Chats

- Create and manage groups

- Add/remove participants

- Group admin privileges

- Group metadata (name, image)

## 📞 Voice Calls

- One-to-one real-time voice calls

- Call accept / reject

- Call duration tracking

- Missed call history

## 🎥 Video Calls

- One-to-one video calls

- Camera and microphone controls

- Call reconnection handling

- Adaptive streaming

## Status Feature

- Text / image / video status

- 24-hour auto-expiry

- View tracking

- Privacy control

## 🔔 Notifications

- New message alerts

- Incoming call notifications

- Offline notification handling

## 📁 Media Sharing

- Image, video, and audio messages

- File size validation

- Secure media URLs

## System Design Highlights
- Real-time messaging using WebSockets

- Voice & video calling using WebRTC

- Stateless backend for scalability

- Redis for presence and socket mapping

- Optimized database queries with indexing

- Separation of concerns (API, sockets, media)

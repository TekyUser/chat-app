# Message Website

This project is a real-time chat website built using Django, React, and Vite. Users can create or join rooms, send messages, and share images without the need for registration. The system uses cookies to identify user messages and ensures a seamless chat experience similar to popular messaging apps.

## Features

- **Room Creation and Join**: Users can create a room or join an existing room by entering a room code.
- **Custom Username**: Users can set a unique username for each room without needing to register or log in.
- **Real-time Messaging**: Chat messages are sent and received in real-time using WebSockets.
- **User Message Identification**: The user’s messages are styled differently (right-aligned with a unique color) using cookies to distinguish them from other users' messages (left-aligned).
- **Image Uploading**: Users can upload images as part of their chat messages.

## Tech Stack

- **Backend**: Django with Django Channels for WebSocket support
- **Frontend**: React with Vite for fast development and live reloading
- **WebSockets**: Real-time communication using Django Channels
- **Database**: SQLite (can be changed for production)
- **Axios**: For handling HTTP requests between the frontend and backend

## Installation Guide

### Prerequisites

- Python 3.x
- Node.js and npm (or Yarn)
- Git

### Backend Setup (Django)

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd message_website/backend

# Real-time Chat Application

A feature real-time chat application with file sharing capabilities, built with Node.js, Express, Socket.IO, and PostgreSQL.

## Features

- Real-time messaging
- File upload and sharing
- User authentication and authorization
- Message history and search
- User presence detection
- Activity logging
- API documentation with Swagger
- Rate limiting
- Token blacklisting
- File processing queue

## Prerequisites

- Node.js (v14 or higher)
- PostgreSQL
- Redis (for job queue)

## Installation

1. Clone the repository: 

# IDE
.idea/
.vscode/
*.swp
*.swo
.DS_Store

# Test coverage
coverage/

# Production build
dist/
build/

# Temporary files
.tmp/
.temp/

## API Endpoints

- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout
- `POST /api/files/upload` - Upload files
- `GET /api/files/downloads/:fileId` - Download file
- `GET /api/messages` - Get message history

## WebSocket Events

- `new_message` - New message notification
- `typing_status` - User typing indicator
- `user_status` - User online/offline status
- `message_deleted` - Message deletion notification

## Security Features

- JWT authentication
- Password hashing
- Token blacklisting
- File type validation
- Rate limiting
- CORS protection
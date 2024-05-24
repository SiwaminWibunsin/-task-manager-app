
# Task Management System

## Description
This project is a task management system that allows users to create, edit, delete, and assign tasks to others. It includes features for tracking task status, setting deadlines, and notifications.

## Technologies Used
- **Frontend**: React, Redux, Material-UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Deployment**: Docker, Kubernetes

## How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/SiwaminWibunsin/task-management-system.git
   cd task-management-system
   ```

2. Build and run the application using Docker Compose
   ```bash
   docker-compose up --build
   ```

3. Access the application
   - Backend API: `http://localhost:5000`
   - Frontend: `http://localhost:3000`

## Features
- User authentication (register and login)
- Task creation, editing, deletion
- Task assignment to other users
- Task status tracking
- Deadline setting and notifications

## Future Enhancements
- Add more detailed user roles and permissions
- Implement real-time notifications using WebSockets
- Enhance UI with more interactive elements

<div align="center">

TaskSync

A focused workspace for planning, prioritizing, and completing everyday tasks.

TaskSync is a modern full-stack productivity application with user access, guest mode, priority-based task management, due dates, smart filters, and visual progress insights.

<br />







<br />



<br />

Overview · Features · Tech Stack · Getting Started · Roadmap

</div>

Overview

TaskSync provides a calm, organized environment for managing daily work without unnecessary complexity. Users can create a personal account or enter immediately through guest mode, then organize tasks using priorities and deadlines.

Built-in search, status filters, priority filters, and progress insights help users understand what needs attention and what has already been completed.





Purpose

Simple and focused task management

Access

Registered account or guest mode

Core workflow

Create, prioritize, track, and complete tasks

Experience

Responsive interface with light and dark themes

<!-- Add a full-width dashboard screenshot here.

![TaskSync Dashboard](./assets/tasksync-dashboard.png)

-->

Features

Task Management

Create and manage personal tasks

Mark tasks as pending or completed

Assign High, Medium, or Low priority

Add deadlines using due dates

View live pending and completed counts

Search and Organization

Search tasks instantly by text

Filter tasks by completion status

Filter tasks by priority level

Review priority distribution and progress insights

Access and Experience

Create a personal user account

Log in to an existing workspace

Continue instantly using guest mode

Switch between light and dark themes

Use the dashboard across desktop and mobile screens

Tech Stack

Layer

Technology

Responsibility

Frontend

React, Vite, CSS

Interface and client-side experience

Backend

Node.js, Express.js

REST API and server-side logic

Database

PostgreSQL

Users and persistent task data

Deployment

Vercel

Live frontend deployment

Project Structure

todo-fullstack/
├── backend/              # Express API and database logic
│   ├── controllers/
│   ├── routes/
│   └── server.js
│
└── frontend/             # React + Vite application
    ├── src/
    │   ├── components/
    │   └── pages/
    └── package.json

Update this tree if your repository uses different directory names.

Getting Started

Prerequisites

Make sure the following are installed:

Node.js

PostgreSQL

Git

1. Clone the repository

git clone <your-repository-url>
cd todo-fullstack

2. Configure the backend

cd backend
npm install

Create a .env file inside the backend directory and add the environment variables required by your implementation:

DATABASE_URL=your_postgresql_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000

Start the backend server:

npm start

3. Configure the frontend

Open a second terminal:

cd frontend
npm install
npm run dev

Vite will display the local development URL in the terminal.

Roadmap

Task categories and custom tags

Recurring tasks

Reminder notifications

Drag-and-drop task ordering

Calendar-based task view

Progressive Web App support

Shared lists and collaboration

Contributing

Contributions and suggestions are welcome.

Fork the repository

Create a feature branch: git checkout -b feature/your-feature

Commit your changes: git commit -m "Add your feature"

Push the branch: git push origin feature/your-feature

Open a pull request

Author

Atharva Padwal
IT Engineering Student · Full-Stack Developer




<div align="center">

If you find TaskSync useful, consider giving the repository a star.

Built with consistency, curiosity, and a focus on better everyday productivity.

</div>

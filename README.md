# Project Hub

Project Hub is a modern, full-stack workspace coordination platform. Built with a clean and intuitive interface, it allows teams to manage their workflows using an interactive, Kanban-style board that syncs instantly across all devices using WebSockets.

## Core Features
- **Workspaces & Collaboration**: Create unique team projects and invite users effortlessly.
- **Drag-and-Drop Workflow**: Seamlessly move tasks between stages in real-time.
- **Instant Sync**: Powered by Socket.io, the application ensures you never need to refresh the page to see a teammate's updates.
- **Live Chat & Notifications**: Discuss tasks directly in the task modal and receive instant toast notifications.

## Tech Stack
- **Client**: React, Vite, Zustand, Tailwind CSS, `@hello-pangea/dnd`
- **Server**: Node.js, Express, MongoDB
- **Real-time Engine**: Socket.io

## Setup Instructions
1. Run `npm install` and `npm run dev` in the `/backend` folder.
2. Run `npm install` and `npm run dev` in the `/frontend` folder.
3. Open `http://localhost:5173`.

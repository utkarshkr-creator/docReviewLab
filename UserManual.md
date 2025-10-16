# Streamify – Real-time Chat and Video Application

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Tech stack](#tech-stack)
- [Installation and setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
Streamify is a full-stack web application for secure, real‑time chat and video calls. It uses WebRTC for peer‑to‑peer media and Socket.IO for instant message updates. Authentication is handled with JSON Web Tokens (JWT).

## Objectives
- Build a modern real‑time communication platform.
- Provide instant chat, video calling, and file sharing features.
- Maintain security and privacy with encryption and role‑based access control (RBAC).

## Tech stack
| Layer        | Technology                    |
| :----------- | :---------------------------- |
| Frontend     | React (Vite), Tailwind CSS    |
| Backend      | Node.js, Express.js           |
| Database     | MongoDB with Mongoose         |
| Communication| Socket.IO, WebRTC             |
| Authentication| JWT, bcrypt                  |
| Deployment   | Render or Vercel              |

## Installation and setup

### Prerequisites
Install the following:
- Node.js (version 18 or later)
- MongoDB (local or Atlas)
- npm or yarn

### Steps
```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/streamify.git
cd streamify

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env
# Set values for MONGO_URI, JWT_SECRET, and PORT

# 4. Start the development server
npm run dev
```

## Usage
- Open the app in your browser at `http://localhost:5173` (or the port shown in the console).
- Create an account or log in with existing credentials.
- Start a chat or initiate a video call with another user.
- Share files during a chat session if enabled.

## Contributing
1. Fork the repository.
2. Create a feature branch: `git switch -c feature/<short-name>`.
3. Commit changes with conventional messages: `feat: add message typing indicator`.
4. Push the branch and open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
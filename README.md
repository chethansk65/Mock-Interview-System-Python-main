# Mock Interview System

This project is a full-stack Mock Interview System that helps users practice interviews, receive feedback, and improve their skills. It consists of a React frontend (client) and a Python backend (server).

---

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Client (Frontend)](#client-frontend)
- [Server (Backend)](#server-backend)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [License](#license)

---

## Features
- Simulated interview experience
- Real-time face recognition and emotion analysis
- AI-generated interview questions based on job role and experience
- Automated review and feedback
- 3D model and animation integration

---

## Project Structure

```
Mock-Interview-System-Python-main/
│
├── client/           # React frontend
│   ├── public/       # Static files, assets, 3D models, face models
│   ├── src/          # React components, pages, CSS, utilities
│   └── package.json  # Frontend dependencies and scripts
│
├── server/           # Python backend
│   ├── app.py        # Main backend server (Flask/FastAPI)
│   └── functions/    # Backend logic: question, emotion, review generation
│
└── package.json      # Project-level dependencies/scripts (if any)
```

---

## Client (Frontend)

- **Framework:** React.js
- **Key Features:**
  - User interface for mock interviews
  - 3D model rendering (robot, Rubik's cube)
  - Real-time face recognition using pre-trained models
  - Animated feedback and review display
- **Main Files/Folders:**
  - `public/`: Contains static assets, 3D models, face detection models
  - `src/pages/`: Main pages (Home, Interview, Review)
  - `src/components/`: Reusable UI components and utilities
  - `src/css/`: Styling for the app
- **How to Run:**
  1. Navigate to the `client` folder: `cd client`
  2. Install dependencies: `npm install`
  3. Start the frontend: `npm start`
  4. The app will run on [http://localhost:3000](http://localhost:3000)

---

## Server (Backend)

- **Language:** Python 3.12+
- **Framework:** Flask (or FastAPI)
- **Key Features:**
  - API endpoints for question generation, emotion analysis, and review
  - Uses AI/ML models for face and emotion recognition
  - Generates interview questions and feedback based on user input
- **Main Files/Folders:**
  - `app.py`: Main server file
  - `functions/`: Contains logic for emotion analysis, question and review generation
- **How to Run:**
  1. Navigate to the `server` folder: `cd server`
  2. (Optional) Create a virtual environment: `python -m venv .venv && .venv\Scripts\activate`
  3. Install dependencies: `pip install -r requirements.txt`
  4. Start the backend: `python app.py`
  5. The server will run on [http://localhost:5000](http://localhost:5000)

---

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd Mock-Interview-System-Python-main
   ```
2. **Install and run the backend** (see above)
3. **Install and run the frontend** (see above)
4. **Make sure both servers are running for full functionality.**

---

## Usage
- Open [http://localhost:3000](http://localhost:3000) in your browser.
- Follow the prompts to start a mock interview.
- Answer questions, and the system will analyze your responses and emotions.
- Receive automated feedback and review.

---

## License
This project is for educational and demonstration purposes.

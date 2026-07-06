# MockMate - AI Powered Virtual Interview Trainer

MockMate is an AI-powered virtual interview preparation platform that helps students and job seekers practice technical interviews through topic-based mock interview sessions. The application provides an interactive environment where users can answer interview questions, receive AI-generated feedback, and monitor their interview performance over time.

---

## Features

- User Registration and Login Authentication
- Secure JWT Authentication
- AI-powered Interview Question Generation
- Multiple Technical Domains
  - Data Structures & Algorithms
  - Operating Systems
  - DBMS
  - Object-Oriented Programming
  - Computer Networks
- Difficulty Levels
  - Easy
  - Medium
  - Hard
- Interactive Mock Interview Sessions
- AI-based Answer Evaluation
- Interview History Tracking
- Performance Dashboard
- Responsive User Interface

---

## Tech Stack

### Frontend
- React.js
- Vite
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication
- JSON Web Token (JWT)

### AI
- Gemini API (Google AI)

### Development Tools
- Visual Studio Code
- Git
- GitHub
- npm

---

## Project Structure

```
MockMate/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── README.md
└── package.json
```

---

## Workflow

1. Register a new account or log in.
2. Select the interview topic.
3. Choose the desired difficulty level.
4. AI generates interview questions.
5. Answer each interview question.
6. AI evaluates the responses.
7. View interview score and feedback.
8. Access previous interview history for performance tracking.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/MockMate.git
```

### Navigate to the Project

```bash
cd MockMate
```

### Install Frontend Dependencies

```bash
cd frontend
npm install
```

### Install Backend Dependencies

```bash
cd ../backend
npm install
```

---

## Run the Project

### Start Backend

```bash
npm start
```

or

```bash
npm run dev
```

### Start Frontend

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file inside the backend directory.

```env
PORT=5000
MONGODB_URI=Your_MongoDB_URI
JWT_SECRET=Your_JWT_Secret
GEMINI_API_KEY=Your_Gemini_API_Key
```

---

## Screenshots

Add screenshots of the following pages:

- Login Page
- Register Page
- Dashboard
- Topic Selection
- Interview Session
- Result Page
- Performance History

---

## Future Enhancements

- Voice-based Interview Support
- Real-time Speech Recognition
- Webcam-based Interview Simulation
- Resume Upload and Analysis
- Company-specific Interview Questions
- Coding Interview Support
- Detailed Analytics Dashboard
- Admin Panel
- Leaderboard
- Interview Report PDF Generation

---

## Learning Outcomes

- Full Stack Web Development
- REST API Development
- JWT Authentication
- MongoDB Database Management
- React Component Architecture
- AI Integration using Gemini API
- CRUD Operations
- State Management
- API Integration

---

## Contributors

- Sahithi Rayudu

---

## License

This project is developed for educational purposes.

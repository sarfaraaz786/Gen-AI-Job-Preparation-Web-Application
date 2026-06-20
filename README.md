# Gen AI Job Preparation Web Application

A full-stack MERN application that helps users prepare for job interviews using AI-generated interview questions and feedback.

## Features

* User Registration and Login
* Secure Authentication using JWT
* AI-Powered Interview Question Generation
* Interview Feedback and Reports
* Protected Routes

## Tech Stack

**Frontend**

* React
* Vite
* SCSS
* Axios

**Backend**

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Gemini API

## Project Structure

```text
Gen-AI-Job-Preparation-Web-Application/
├── Frontend/
└── Backend/
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/sarfaraaz786/Gen-AI-Job-Preparation-Web-Application.git
cd Gen-AI-Job-Preparation-Web-Application
```

### Install Dependencies

```bash
cd Backend
npm install

cd ../Frontend
npm install
```

### Run the Application

Start Backend:

```bash
cd Backend
npm run dev
```

Start Frontend:

```bash
cd Frontend
npm run dev
```

## Environment Variables

Create a `.env` file in the `Backend` folder and add your required environment variables.

```env
PORT=
MONGO_URI=
JWT_SECRET=
GEMINI_API_KEY=
```

## Author

**MD Sarfaraaz**

GitHub: https://github.com/sarfaraaz786

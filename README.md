# AI-Powered Real-Time Feedback System

This project is an **AI-powered real-time feedback system** where users can submit feedback through a form. The feedback is analyzed in real-time for sentiment (positive, negative, neutral) using Hugging Face's sentiment analysis API, and the result is displayed to the user in a pop-up window.

## Features

- **User Feedback Submission**: Users can submit their name, email, and feedback through the form.
- **Real-Time Sentiment Analysis**: The submitted feedback is analyzed for sentiment (positive, negative, or neutral).
- **Result Display**: The sentiment analysis result is shown in a popup using SweetAlert2.
- **Database Storage**: Feedback and sentiment analysis results are stored in MongoDB for future reference.

## Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **AI Model**: Hugging Face API (sentiment analysis)
- **Database**: MongoDB
- **Popup Library**: SweetAlert2

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or higher)
- MongoDB
- Hugging Face account and API Key

## Dependencies

### Backend Dependencies

- **express**: Fast, unopinionated, minimalist web framework for Node.js.
- **mongodb**: Official MongoDB driver for Node.js.
- **axios**: Promise-based HTTP client for the browser and Node.js.
- **dotenv**: Loads environment variables from `.env` file.
- **@huggingface/inference**: Hugging Face inference API for sentiment analysis.

### Frontend Dependencies

- **react**: A JavaScript library for building user interfaces.
- **axios**: HTTP client for making API requests.
- **sweetalert2**: Beautiful, responsive, customizable JavaScript popups.
- **tailwindcss**: A utility-first CSS framework.
## Live Link

You can access the live version of the application at: [Live Feedback System](https://real-time-feedback-system.vercel.app/)

## Server-Side GitHub Repository

The server-side code is available at: [Real-Time Feedback System Server](https://github.com/tafiya/real-time-feedback-system-server)   
  
  
## Getting Started
Follow the steps below to set up and run the project on your local machine

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/real-time-feedback-system.git
cd real-time-feedback-system

## 2. Set Up the Backend

Navigate to the server directory:
cd server
Install the dependencies:
npm install
Create a .env file in the server directory and add the following environment variables:
DB_USER=fedbackUser
DB_PASSWORD=rEBjx5366I7gg1AK
HF_API_KEY=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
Run the backend server:
node index.js

3. Set Up the Frontend
Navigate to the client directory:
cd client
Install the dependencies:
npm install
Run the frontend app:
npm run dev
